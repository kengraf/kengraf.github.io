# kengraf.github.io

This site is motivated by providing concrete examples of security and serverless deployments for the classes I teach at UNH.  

The CI/CD process:
A local clone of this repo for basic dev, test and debugging.  
When I hit a stable point (need to pause work for: sleep, golf, bills mafia) the local clone is pushed.  
A Github workflow pushes the repo update to AWS S3.  
The S3 bucket <http://kengraf.com.s3-website.us-east-2.amazonaws.com>.  
The bucket is fronted by a AWS CloudFront distribution <https://d1r0kizfj5s76j.cloudfront.net>  
Which is pointed to by <https://kengraf.com> with a Route53 DNS alias.   

Easy, Peasy, no server.  Or better yet no $$.
work to do
github workflow to s3

| Item              | Group | pic | blurb |
| :---------------- | :------: | ----: | :--- |
| people  |  travel    |   | scotland, nz, ireland,etc gallery |
| people  | family     |   | gallery  |
| people  | gary-pics     |   | gallery  |
| hobby  |  golf    |   | top #  |
| hobby  | recipes     |   | site  |
| hobby  | chess     |   | journey puzzles  |
| hobby  | cyber puzzles     |   | random page  |
| history |  unh-cyber  |   | site  |
| history |  securityxing    |   | site  |
| tech  |  pi    |   | site  |
| tech  |  nadialin    |   | site  |
| tech  |  it666    |   | site  |
| tech  | it718     |   | site  |
| tech  | github     |   | site  |
