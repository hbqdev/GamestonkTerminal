## Get underlying data 
### common.ta.zlma(data: pandas.core.series.Series, length: int = 50, offset: int = 0) -> pandas.core.frame.DataFrame

Gets zero-lagged exponential moving average (ZLEMA) for stock

    Parameters
    ----------
    data: pd.Series
        Dataframe of dates and prices
    length: int
        Length of EMA window
    offset: int
        Length of offset

    Returns
    ----------
    df_ta: pd.DataFrame
        Dataframe containing prices and EMA
