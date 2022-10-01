Sample HTML document
================
Ranjitprakash Sundaramurthi
2022-10-01

## Answer 8

## Calculating the Area and Perimeter of a Circle

The Area of a circle is calculated by multiplying pi with the square of
the radius. Pi is equivalent to 3.14 and the radius is the distance of
each point on the circle from its center. The perimeter is calculated as
double the product of pi and radius

Below are code chunks to calculate the area and perimeter of circle with
radius r.

``` r
r <- 10
p <- 3.14

circle_area <- p*r^2
circle_area
```

    ## [1] 314

``` r
circle_perimeter = 2*p*r
circle_perimeter
```

    ## [1] 62.8

## Calculating the Area and Perimeter of a Square

Unlike a Circle which can be considered to have infinite sides, a square
has only 4 sides. The area of a square is calculated by multiplying the
length of 2 of its adjacent sides. The perimeter of a square is
calculated as twice the sum of the length of its adjacent sides.

Below are code chunks to calculate the area and perimeter of a square
with sides c and d.

``` r
c <- 10
d <- 20

square_area <- c*d
square_area
```

    ## [1] 200

``` r
square_perimeter <- 2*(c+d)
square_perimeter
```

    ## [1] 60

## Default template for Markdowns below - Untouched

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](Computing_area_perimeter_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
