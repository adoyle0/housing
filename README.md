# Housing Prediction
======

[Full Data Dictionary](data/dictionary.txt)

### Data used from Dictionary
|Feature Name|Data Type|Description|
|------------|---------|-----------|
|gr_liv_area|int|Total sq_ft of above grade(ground) living space|
|age|int|Calculated age of house at time of sale|
|lot_area|int|Size of house lot in sq_ft|
|overall_qual|int|Range from 1-10 rating of overall material and finish of house. 1 being very poor and 10 very excellent|
|fireplaces|int|number of fireplaces in the house|
|full_bath|int|number of full bathrooms in the house|
|half_bath|int|number of half batherooms in the house|
|neighborhood|dummy encoded|Neighborhood the house exists in|
|central_air|true/false|if the house has central air or not|
|ms_zoning|dummy encoded|zoning of property lot|
|street|dummy encoded|if the house is on a paved or dirt road|
|land_contour|dummy encoded|if the property is considered flat or banked|
|lot_config|dummy encoded|inside, corner, cul-de-sac, etc. type lot|
