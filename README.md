# kengraf.github.io

This site is motivated by providing concrete examples of security and serverless deployments for the classes I teach at UNH.  

The CI/CD process:
A local clone of this repo for basic dev, test and debugging.  
When I hit a stable point (need to pause work for: sleep, golf, bills mafia) the local clone is pushed.  
A Github workflow pushes the repo update to AWS S3.  
The S3 bucket not internet accessible.  
The bucket is fronted by a AWS CloudFront distribution (https://d1r0kizfj5s76j.cloudfront.net)  
which is pointed to by (https://kengraf.com)  

Easy, Peasy, no server.  Or better yet no $$.


| Item              | Group | pic | blurb |
| :---------------- | :------: | ----: | :--- |
| people &places | gary     |   | page & gallery  |
| people  |  travel    |   | scotland, nz, ireland,etc gallery |
| people  |   picuda   |   |  page |
| people  |   bills   |   | page  |
| people  | cross roads     |   | site  |
| people  | family     |   | gallery  |
| hobby  |  golf    |   | top #  |
| hobby  | recipes     |   | site  |
| hobby  | chess     |   | journey puzzles  |
| hobby  | misc puzzles     |   | random page  |
| history |  unh-cyber  |   | site  |
| history |  securityxing    |   | site  |
history pics bbc, nutpu, entegrity, sanctum, watchfire, intel, liberty
| tech  |  pi    |   | site  |
| tech  |  nadialin    |   | site  |
| tech  |  cyber puzzles    |   | random page  |
| tech  |  it666    |   | site  |
| tech  | it718     |   | site  |
| tech  | github     |   | site  |
|   |      |   |   |
|   |      |   |   |