# Selecting the Search App
- Splunk is organized into a number of apps each of which can contain separate datasets, dashboards, and configuration options.
- On the left hand side select Search & Reporting

# Term Searches
- Select a time in the time picker
- type a search in the main search bar (failed)

# Search Results
- Timeline (at the top, gives a summary of the distribution of events over time
- fields bar is on the left
- main events list to the right of that

# fields in the search results
- Host (typically the HN, IP addr, FQDN of the host from which the event originated from
- Source: the name of the file or stream from which the even originates. For data monitored from files and directories , it is the full path, such as /archive/server1/var/log/messages.0. For network-based data sources, it is the protocol and port such as UDP:514
- Sourcetype - the format of the data input from which it originates, such as access_combined or cisco_syslog. The source type determines how your data is to be formatted.
