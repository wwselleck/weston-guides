# Postgres Guide

### Quick Reference
#### Dates
+ Convert from unix time (seconds) to timestamp
	+ `(TIMESTAMP 'epoch' + myunixtime * INTERVAL '1 Second ')`
+ Convert from unix time (milliseconds) to timestamp
	+ `(TIMESTAMP 'epoch' + myunixtime * INTERVAL '.001 Second ')`