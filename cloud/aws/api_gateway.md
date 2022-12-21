# API Gateway

https://www.youtube.com/watch?v=yfJZc3sJZ8E

    Arch: 1) Edge 2) Private - VPC / Regional
    Config: 6 ways: console, awscli, SAM (much), aws CL, swagger, CDK 
    Integration backend: Lamdba function, http, mock, aws service, vpc link (eLoad balancing - nlb)
    VTL

### Throttling requests

   default 10K per seconds per region
   API level (key token)

https://aws.amazon.com/en/blogs/compute/building-well-architected-serverless-applications-regulating-inbound-request-rates-part-1/

https://aws.amazon.com/en/blogs/compute/building-well-architected-serverless-applications-regulating-inbound-request-rates-part-2/

https://aws.amazon.com/en/blogs/compute/understanding-vpc-links-in-amazon-api-gateway-private-integrations/

https://aws.amazon.com/en/blogs/compute/building-better-apis-http-apis-now-generally-available/

https://aws.amazon.com/en/blogs/compute/generating-rest-apis-from-data-classes-in-python/

https://aws.amazon.com/en/blogs/compute/building-a-serverless-url-shortener-app-without-lambda-part-3/

https://aws.amazon.com/en/blogs/compute/architecting-multiple-microservices-behind-a-single-domain-with-amazon-api-gateway/

https://aws.amazon.com/en/blogs/compute/from-poll-to-push-transform-apis-using-amazon-api-gateway-rest-apis-and-websockets/

https://aws.amazon.com/en/blogs/compute/deploying-a-personalized-api-gateway-serverless-developer-portal/

https://aws.amazon.com/en/blogs/compute/amazon-api-gateway-adds-support-for-aws-waf/

https://aws.amazon.com/en/blogs/compute/support-for-multi-value-parameters-in-amazon-api-gateway/

https://aws.amazon.com/en/blogs/compute/overriding-request-response-parameters-and-response-status-in-amazon-api-gateway/

https://aws.amazon.com/en/blogs/compute/protecting-your-api-using-amazon-api-gateway-and-aws-waf-part-2/

https://aws.amazon.com/en/blogs/compute/error-handling-patterns-in-amazon-api-gateway-and-aws-lambda/

https://aws.amazon.com/en/blogs/compute/amazon-api-gateway-mapping-improvements/

## VPC links (endpoint)

https://docs.aws.amazon.com/en/apigateway/latest/developerguide/apigateway-developer-portal.html

https://aws.amazon.com/en/blogs/compute/configuring-private-integrations-with-amazon-api-gateway-http-apis/
> API Gateway (private integration) -> API VPC link (EndPoint) -> Application Load balancer -> ECS EC2s
> https://www.youtube.com/watch?v=gdhwKuVOHUg

https://aws.amazon.com/en/blogs/compute/protecting-your-api-using-amazon-api-gateway-and-aws-waf-part-i/

https://aws.amazon.com/en/blogs/compute/introducing-amazon-api-gateway-private-endpoints/

## Client certificate (EC2)
## Custom domain

## Security
https://aws.amazon.com/en/blogs/compute/evaluating-access-control-methods-to-secure-amazon-api-gateway-apis/

https://aws.amazon.com/en/blogs/compute/introducing-mutual-tls-authentication-for-amazon-api-gateway/

https://aws.amazon.com/en/blogs/compute/automating-mutual-tls-setup-for-amazon-api-gateway/

https://aws.amazon.com/en/blogs/compute/introducing-iam-and-lambda-authorizers-for-amazon-api-gateway-http-apis/

https://aws.amazon.com/en/blogs/compute/centralizing-security-with-amazon-api-gateway-and-cross-account-aws-lambda-authorizers/

https://aws.amazon.com/en/blogs/compute/control-access-to-your-apis-using-amazon-api-gateway-resource-policies/

https://aws.amazon.com/en/blogs/compute/using-enhanced-request-authorizers-in-amazon-api-gateway/

https://aws.amazon.com/en/blogs/compute/how-to-remove-boilerplate-validation-logic-in-your-rest-apis-with-amazon-api-gateway-request-validation/

https://aws.amazon.com/en/blogs/compute/authorizing-access-through-a-proxy-resource-to-amazon-api-gateway-and-aws-lambda-using-amazon-cognito-user-pools/

## Mapping
https://aws.amazon.com/en/blogs/compute/using-multiple-segments-in-amazon-api-gateway-base-path-mapping/

## Data
https://aws.amazon.com/en/blogs/compute/handling-binary-data-using-amazon-api-gateway-http-apis/

## Test
https://aws.amazon.com/en/blogs/compute/using-serverless-to-load-test-amazon-api-gateway-with-authorization/

https://aws.amazon.com/en/blogs/compute/performing-canary-deployments-for-service-integrations-with-amazon-api-gateway/

## Monitoring
https://aws.amazon.com/en/blogs/compute/troubleshooting-amazon-api-gateway-with-enhanced-observability-variables/

## Function
https://aws.amazon.com/en/blogs/compute/introducing-amazon-api-gateway-service-integration-for-aws-step-functions/

##
https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-known-issues.html
> https://news.ycombinator.com/item?id=34079591