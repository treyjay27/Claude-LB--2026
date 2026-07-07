## Core Setup

- [x] Create GitHub repository
- [ ] Add README
- [x] Add project goals
- [x] Add technical information
- [x] Add daily log
- [x] Add project checklist
- [ ] Keep daily progress documented
- [x] Create a clear roadmap
- [x] Track major issues and fixes

## Local Development Setup

- [x] Set up project folder on local machine
- [x] Install Python
- [x] Set up code editor
- [x] Set up terminal workflow
- [ ] Connect local project to GitHub
- [ ] Push local updates to GitHub
- [x] Create clean folder structure
- [ ] Add `.gitignore`
- [ ] Keep secrets out of GitHub
- [ ] Use environment variables for API keys and tokens

## Hardware / Always-On Setup

- [x] Set up MINISFORUM UM880 Plus Mini PC
- [x] Confirm stable internet connection
- [x] Confirm the machine can run for long testing sessions
- [x] Set power settings so the machine does not sleep during testing
- [x] Confirm remote access if needed
- [x] Set up backups for important project files
- [x] Confirm LB can run without needing my main computer open

## Claude / AI Assistant Layer

- [ ] Define what Claude will help with
- [ ] Decide what LB can do automatically
- [ ] Decide what requires my approval
- [ ] Create clear prompts for decision support
- [ ] Build simple test prompts
- [ ] Track good and bad responses
- [ ] Improve prompt structure over time
- [ ] Prevent LB from making major decisions without approval

## Telegram Alerts

- [x] Create Telegram bot
- [x] Get Telegram bot running successfully
- [x] Confirm Telegram can send messages
- [x] Save Telegram token safely
- [x] Connect Telegram alerts to LB code
- [x] Send test alert from local script
- [x] Format alerts clearly
- [ ] Add item name, price, link, and reason for alert
- [ ] Add profit estimate to resale alerts
- [ ] Add confidence level to alerts
- [ ] Add error alerts if something breaks

## Discord Integration

- [ ] Decide which Discord servers/channels LB should monitor
- [ ] Confirm legal/safe way to read Discord alerts
- [ ] Create Discord bot or approved access method
- [ ] Connect Discord to local script
- [ ] Read test messages from Discord
- [ ] Filter only useful deal alerts
- [ ] Ignore irrelevant channels
- [ ] Ignore Pokémon-related alerts
- [ ] Extract item name from alert
- [ ] Extract price from alert
- [ ] Extract store/source from alert
- [ ] Extract product link from alert
- [ ] Extract category when possible
- [ ] Log received Discord alerts
- [ ] Handle duplicate alerts
- [ ] Handle bad or incomplete alerts
- [ ] Send Discord test alert into Telegram

## eBay Resale Research

- [ ] Decide how LB will search eBay comps
- [ ] Research eBay sold comps options
- [ ] Test eBay search manually
- [ ] Test eBay sold listing search
- [ ] Pull item title from Discord alert
- [ ] Search eBay sold listings using item title
- [ ] Filter out irrelevant eBay results
- [ ] Estimate average sold price
- [ ] Estimate realistic resale range
- [ ] Track number of sold comps found
- [ ] Flag low-confidence comp results
- [ ] Estimate eBay fees
- [ ] Estimate shipping cost
- [ ] Calculate expected profit
- [ ] Calculate profit margin
- [ ] Filter out low-profit items
- [ ] Add “buy / maybe / pass” decision output
- [ ] Send good resale alerts to Telegram

## Resale Decision Rules

- [ ] Set minimum profit threshold
- [ ] Set minimum margin threshold
- [ ] Set category rules
- [ ] Ignore Pokémon
- [ ] Ignore items with weak comps
- [ ] Ignore items with too much competition
- [ ] Ignore items that are too large or hard to ship
- [ ] Flag items with strong sell-through
- [ ] Flag items with fast resale potential
- [ ] Add confidence score
- [ ] Add reason for each recommendation
- [ ] Track accepted alerts
- [ ] Track rejected alerts
- [ ] Improve rules based on real results

## News Filtering

- [ ] List news sources LB should monitor
- [ ] Test accessible news links
- [ ] Identify sources that block bot traffic
- [ ] Find correct accessible links
- [ ] Look into RSS feeds
- [ ] Look into supported APIs
- [ ] Build workaround for blocked sources
- [ ] Read article titles
- [ ] Summarize news items
- [ ] Filter irrelevant news
- [ ] Track important topics
- [ ] Send major news alerts to Telegram
- [ ] Keep source links in alerts
- [ ] Separate resale news from market news

## Trading Research Support

- [ ] Decide what market information LB should track
- [ ] Track stocks I care about
- [ ] Track sectors I care about
- [ ] Read market news
- [ ] Summarize important market updates
- [ ] Compare news to price movement
- [ ] Explain why a stock may be moving
- [ ] Generate trade ideas for review
- [ ] Mark ideas as watchlist only
- [ ] Require human approval before any trade
- [ ] Keep trade research separate from actual trading
- [ ] Track why an idea was suggested
- [ ] Track whether the idea worked or failed

## Email Support

- [ ] Decide which email account LB can access
- [ ] Define what emails LB should read
- [ ] Summarize important emails
- [ ] Ignore junk or low-value emails
- [ ] Flag emails that need a response
- [ ] Draft email replies for review
- [ ] Never send important emails without approval
- [ ] Track unread important emails
- [ ] Alert me about time-sensitive emails
- [ ] Keep personal data handling safe

## Calendar and Scheduling

- [ ] Connect calendar tools
- [ ] Read upcoming events
- [ ] Summarize daily schedule
- [ ] Alert me about important events
- [ ] Help organize reminders
- [ ] Help plan tasks around calendar events
- [ ] Connect scheduling information to Skylight Calendar
- [ ] Display important schedule items clearly
- [ ] Avoid duplicate calendar entries
- [ ] Require approval before making major schedule changes

## Weekly Tee Times

- [ ] Identify golf courses to check
- [ ] Decide preferred tee time windows
- [ ] Decide preferred days of the week
- [ ] Check available tee times
- [ ] Filter tee times by price
- [ ] Filter tee times by location
- [ ] Filter tee times by time of day
- [ ] Alert me when a good tee time appears
- [ ] Add tee time options to Telegram alerts
- [ ] Add selected tee times to calendar
- [ ] Display tee times on Skylight Calendar
- [ ] Avoid booking without approval unless explicitly allowed later

## Skylight Calendar

- [ ] Confirm Skylight Calendar sync setup
- [ ] Confirm personal calendar is syncing
- [ ] Confirm shared calendar is syncing
- [ ] Add tee times to calendar
- [ ] Add bills or reminders if useful
- [ ] Display important events clearly
- [ ] Use Skylight as a visual dashboard for schedules
- [ ] Troubleshoot missing calendar entries
- [ ] Document any sync issues

## Task and Reminder Automation

- [ ] Create daily task list
- [ ] Create reminders
- [ ] Track personal projects
- [ ] Track project deadlines
- [ ] Send reminders through Telegram
- [ ] Prioritize tasks by importance
- [ ] Summarize what needs attention today
- [ ] Keep completed tasks logged
- [ ] Avoid sending too many notifications

## Logging and Monitoring

- [ ] Log Discord messages received
- [ ] Log filtered-out alerts
- [ ] Log eBay comp results
- [ ] Log Telegram alerts sent
- [ ] Log errors
- [ ] Log failed news source attempts
- [ ] Log important decisions
- [ ] Keep logs readable
- [ ] Rotate or clean logs over time
- [ ] Use logs to improve LB

## Security and Safety

- [ ] Keep API keys out of GitHub
- [ ] Keep tokens out of screenshots
- [ ] Use environment variables
- [ ] Limit permissions for each integration
- [ ] Avoid giving unnecessary account access
- [ ] Review what data is being stored
- [ ] Avoid storing sensitive personal data when possible
- [ ] Keep private credentials local
- [ ] Document required permissions
- [ ] Make sure important actions require approval
- [ ] Keep a clear audit trail of changes

## Testing

- [ ] Test Telegram alone
- [ ] Test Discord alone
- [ ] Test Discord to Telegram
- [ ] Test eBay lookup alone
- [ ] Test Discord to eBay lookup
- [ ] Test Discord to eBay to Telegram
- [ ] Test Pokémon filter
- [ ] Test bad link handling
- [ ] Test missing price handling
- [ ] Test duplicate alert handling
- [ ] Test low-profit item filtering
- [ ] Test high-profit item alerting
- [ ] Test news source access
- [ ] Test calendar display
- [ ] Test tee time alerts

## Documentation

- [ ] Keep README clean
- [ ] Keep project goals updated
- [ ] Keep technical information updated
- [ ] Keep daily log updated
- [ ] Add screenshots when useful
- [ ] Add examples of alerts
- [ ] Add setup instructions later
- [ ] Add notes about problems solved
- [ ] Add roadmap when ready
- [ ] Keep documentation honest and realistic

## First Major Milestone

- [ ] LB reads a Discord deal alert
- [ ] LB filters the alert
- [ ] LB ignores Pokémon
- [ ] LB searches eBay sold comps
- [ ] LB estimates profit
- [ ] LB sends a Telegram buy alert

## Long-Term Milestone

- [ ] LB becomes a useful personal automation system
- [ ] LB saves time every week
- [ ] LB filters important information
- [ ] LB supports resale decisions
- [ ] LB supports trading research
- [ ] LB helps with email and scheduling
- [ ] LB helps find weekly tee times
- [ ] LB becomes reliable enough to run regularly
