# larcado/nodejs-chrome

latest node.js (with npm) + latest stable Google Chrome

## bundled with latest image
| Package name | Version |
| ------ | ------ |
| node.js | v11.11.0 |
| npm | 6.9.0 |
| Google Chrome | 72.0.3626.121 |

### using example

Can be used for automated CI build of Angular App with testing by Karma

```sh
$ ng test --single-run=true --watch=false --browsers ChromeHeadless
```
