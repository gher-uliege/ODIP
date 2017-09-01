|Gridding tools | [IDL](http://www.harrisgeospatial.com/ProductsandTechnology/Software/IDL.aspx) | [ODV](https://odv.awi.de/) | [IDV](http://www.unidata.ucar.edu/software/idv/) | [(arc)GIS](http://www.unidata.ucar.edu/software/idv/) | [DIVA](https://github.com/gher-ulg/DIVA) | [divand](https://github.com/gher-ulg/divand.jl)|[diva-on-web](http://ec.oceanbrowser.net/emodnet/diva.html) | [SURFER](http://www.goldensoftware.com/products/surfer) | [Ferret](http://ferret.pmel.noaa.gov/Ferret/) | [GNU R](https://www.r-project.org/)| [Panoply](https://www.giss.nasa.gov/tools/panoply/)|
| ------------- | --- | --- | --- | -------- | ---- | ------ | ---------- | ------ | ------ | ----- | -------|
|**Gridding techniques** | Nearest neighbours, inverse distance, bilinear, polynomial, spline, natural neighbours, kriging  |Inverse distance, Variational Inverse Method (VIM) | Inverse distance | Inverse distance, polynomial, spline, natural neighbours, kriging | Variational Inverse Method| Variational Inverse Method| Variational Inverse Method| Nearest neighbour, moving average, linear, inverse distance, radial basis function, (local) polynomial, natural neighbours, minimum curvature, Modified Shepard's Method, kriging| Nearest neighbour, moving average, linear |Inverse distance, moving average, linear, spline, kriging |Linear | 
|**Knowledge of covariances**| Kriging: choice between 4 covariance functions|VIM: covariances implicitly chosen by the shape of the norm|A priori|Kriging: choice between 5 variogram models|VIM: covariances implicitly chosen by the shape of the norm|VIM: covariances implicitly chosen by the shape of the norm|VIM: covariances implicitly chosen by the shape of the norm|Kriging: choice between 10 variogram models or a combination of each|A priori|Kriging: choice between 3 variogram models|A priori|
|**Error estimation**|No|Yes|No|No|Yes|Yes|Yes|No (only RMSE with respect to the data)|No|No|No|
|**Interpolation or analysis?**|Interpolation / Analysis|Interpolation / Analysis|Interpolation|Interpolation / Analysis|Analysis|Analysis|Analysis|Interpolation / Analysis|Interpolation|Interpolation / Analysis|Interpolation|
|**Multivariate analysis**|No|No|No|Yes (cokriging)|Yes|Yes|No|No|No|Yes|No|
|**Scripting / API**|Yes|Yes (API for C++ and Java)|Yes|Yes|Yes|Yes|Yes|Yes|Yes|Yes|Yes (beta)|
|**Physical constraints**|No|Coastlines, advection along isopycnals|No|No|Coastlines, advection fields, ocean bottom|Coastlines, advection fields|Coastlines, advection fields|No|No|No|No|
|**Maximum dimensions**|2D (3D if inverse distance)|2D|2D|2D|2D, pseudo-3D, pseudo-4D|nD|2D|2D|4D|2D|2D|
|**Handling of anisotropy**|Ellipse defining a line of equal influence|Advection along isopycnals|No specific feature|Covariance modeling along each direction|Variable correlation length field, advection fields|Advection fields|Advection fields|Angle of preferred direction|No specific feature|Angle of preferred direction|No specific feature|







