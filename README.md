# android_patches

1. update your local manifest:

~~~
<remote name="gfour" fetch="ssh://git@github.com/LGgFour/" />

<project path="external/patches" name="android_external_patches" remote="gfour" revision="android-10.0" />
~~~

2. apply the patch(es):

~~~
cd <android src path>
git apply external/patches/<patchname>
~~~
