# IEXCloudDotNet
IEXCloudDotNet is a .Net class library allowing easy access to the IEXCloud API

You can find it here https://www.nuget.org/packages/IEXCloudDotNet/

# NEW UPDATE COMING (MAY 2019)
I will be releasing an update in the next week or so that will include SSE Streaming for Quotes, as well as some additional classes implemented. There will also be in official documentation released on the GitHub page for all classes and a brief tutorial. If you want to follow my work, my Facebook is [Cody Rocheleau](https://www.facebook.com/cody.rocheleau1)


# Version 1.0.1.1 (Bug Fix)

### April 1st 2019 Update
Fixed some issues that occured when a null value was returned from the IEXCloud API


## Features 
##### Classes Implemented
- BalanceSheet
- Company
- DelayedQuote
- Dividend
- Earnings
- EffectiveSpread
- HistoricalPrice
- KeyStats
- Logo
- MarketVolumeUS
- News
- OHLC (Open High Low Close)
- PreviousDayPrice
- PriceTarget
- Quote
- SectorPerformance
- VenueVolumn

All classes implement INotifyPropertyChange and are set up to work with binding. 

# Future Updates
- Custom Exception handling
- More class implementations
- Fine tuning of server calls to make calls less expensive
- Asynchronous calls
- HttpClient impementation
