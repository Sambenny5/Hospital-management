Overview:

The hms package provides a simple class for storing durations or time-of-day values and displaying them in the hh:mm:ss format. This class is intended to simplify data exchange with databases, spreadsheets, and other data sources:

Stores values as a numeric vector that contains the number of seconds since midnight
Supports construction from explicit hour, minute, or second values
Supports coercion to and from various data types, including POSIXt
Can be used as column in a data frame
Based on the difftime class
Values can exceed the 24-hour boundary or be negative
By default, fractional seconds up to a microsecond are displayed, regardless of the value of the "digits.secs" option
