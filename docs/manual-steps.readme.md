IF there is no travis.yml file in the root directory you need to create one and add the following lines of code in it

``` yml
env:
  - DOC_SITE_NAME="Component Name"
import: finn/travis-techdocs:publish.yml@master
```
Else. add the above lines in it's appropriate place in your travis.yml
