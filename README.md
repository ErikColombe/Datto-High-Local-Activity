# Datto-High-Local-Activity
Used for Datto API and Query in Excel to pull and manipulate information.

Purpose: The purpose of this code is to be used with an organization's Datto API. After importing the XML query information into Excel this macro can be used to copy the daily Datto sizes across all agents. The code will then manipulate the data to compare the current day and the date last run.  If the growth is higher than 50% of the protected amount the growth will be flagged red. This can help identify if a full backup is taking place to stop problems occurring on smaller agents
