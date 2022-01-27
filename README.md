# Download all contents from Coursera

## Setup `coursera-dl`

pip install coursera-dl

[https://github.com/coursera-dl/coursera-dl](https://github.com/coursera-dl/coursera-dl)


## Create `coursera-dl.conf` file

Place the file namely `coursera-dl.conf` in the directory where to use `coursera-dl `command.
The example of the format is below.

```sh
--username <email>
--password <pass>
--cauth <CAUTH-cookie>
```

## Now, you can use `coursera-dl`

```kotlin
coursera-dl <course name>
```

You can get the course name in the url of the course you would like to get contents.
For example, if you would like to get the contents in a course below,

[https://www.coursera.org/learn/deep-learning-in-computer-vision](https://www.coursera.org/learn/deep-learning-in-computer-vision),

you should type the command below.

```kotlin
coursera-dl deep-learning-in-computer-vision
```

Then, coursera-dl starts downloading.


## References

[https://github.com/coursera-dl/coursera-dl](https://github.com/coursera-dl/coursera-dl)
[https://medium.com/@ootaki.yuuki/how-to-download-all-contents-in-coursera-courses-automatically-963f199be55f](https://medium.com/@ootaki.yuuki/how-to-download-all-contents-in-coursera-courses-automatically-963f199be55f)
[https://ostechnix.com/coursera-dl-a-script-to-download-coursera-videos/](https://ostechnix.com/coursera-dl-a-script-to-download-coursera-videos/)
