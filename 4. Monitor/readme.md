# Azure Cache for Redis
Managed Redis Cache and a PaaS offering

![image](https://github.com/venkatavarunp/AZ-204/assets/130353146/9e91b952-8f3e-49ad-946e-8ecdf9e108cd)

![image](https://github.com/venkatavarunp/AZ-204/assets/130353146/ac9dfe03-bb73-40e0-8ea4-36d605f102b2)

# CDN
a CDN is a set of reverse proxies distributed around the world and cache is stored in the reverse proxies.

![image](https://github.com/venkatavarunp/AZ-204/assets/130353146/0c15d602-d290-4321-84c0-158321ea5d93)

the user API calls are passsed through CDN if the data of API is present in the CDN it will be sent back or else it will be sent from the server and it will be cached

we need to take care of two main things in CDN that are 
- Validation (whether the CDN content is in sync with the server and can be validated by Etag(unique string attached))
- Duration

# Application Insights
## APM 
a software that provides Application level monitoring

![image](https://github.com/venkatavarunp/AZ-204/assets/130353146/90b71c4c-b3b8-4025-80a7-1c909eb1d6f1)

A library that collects the data and plots them in application Insights

every application insights resource has a unique `INSTRUMENTATION KEY` specific to application resources.

