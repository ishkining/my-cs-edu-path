# Notes

HEAD - check does this resource exists
PATCH - change object(special modification)
PUT - create object, not only changing
POST - problem with idempotence

### status codes

202 - Application taking to notice but we havent result rn
409 - object existed

### check list

- Expectations of client should be acknowledged and it should be reflected and with docs
- Api should be abstract
- Client should have freedom in using API
- Earlier define test cases for API
- Solutions should be native to the protocols
- Client always should get actual information whe got result from app