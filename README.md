# IEXCloudDotNet
IEXCloudDotNet is a .Net class library allowing easy access to the IEXCloud API

You can find it here https://www.nuget.org/packages/IEXCloudDotNet/

# NEW UPDATE COMING (SOON!) (UPDATED JULY 2019)
Hello All! Many of you have been asking when the update will be taking place. It is going to happen, I promise. I have been extremely busy working on several other projects and starting my own business, that I have put this one on the back burner. I have the majority of the update complete and am currently testing everything to make sure it is releasable. Give me another week or two, and I will have it published, with a sample program posted here.

Some of the main features of this update include;
- SSE Streaming for Quotes
- Updated Classes
- Extra Exception handling
- Documentation

Some future updates that I am planning include:
- Switching the project over to a .net Standard library to increase support for lower levels of the stack
- CURL streaming
- DEEP API Implementation
- Currency Implementation


[Cody Rocheleau](https://www.facebook.com/cody.rocheleau1)


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
