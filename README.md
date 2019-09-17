# codetest
# Good that I found.
1. It is using Repository Pattern
2. 

# Need to Enhance
1. Instead of using env we will use the Config as env() will not work on the linux environment
2. We will used custom Request Validator in each particular request for example instead of using Generic Request we will use our own request by running this command `php artisan make:request CustomRequest`
3. We will use JOB when sending and accessing third party web services.
4. In BookingRepository we will use GuzzleHttp for easy handle instead of CURL and we will separate the code and add it in the provider folder.
5. The static value like paid, unpaid, professional, rwstranslator, etc. we will add it in the model as a constant variable like so Model::PROFESSIONAL
6. Instead using many elseif we can use switch methods

