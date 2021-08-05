# London_housing_prices

Here’s the mystery we’re going to solve: which boroughs of London have seen the greatest increase in housing prices, on average, over the last two decades?

conclusion -
##steps to answer the question above the following steps were followed.

1) set up - generate/ activate conda env, import packages, import data.

2) observe initial data and format data to have variables in columns and observations in rows, key method is pd.rename and .T for transform.

3) make sure variable labels are removed from columns and rows so only data points in df

4) generate additional varabiles to answer question, Year column was created to allow for aggregation by year as dates gave month ganularity.

5) group by to aggregate data by year and borrow to allow for change in price over time to be assesed.

6) do calculations and create vizulisations to create comparisons that answer buisness question. ratio of price change over 20 years calcuated , sorted and vizulised to show with borrows had the greatest increase in housing price.
