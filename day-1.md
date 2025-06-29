# Daily Learning
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)
```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
Method for binary search in Java
```java
private static int binarySearch(List<Integer> listOfNumbers, int numberToGetIndex) {
        int low = 0;
        int high = listOfNumbers.size() - 1;
        while (low <= high) {
            int middleIndex = (low + high) / 2;
            int numberInMiddle = listOfNumbers.get(middleIndex);

            if (numberToGetIndex == numberInMiddle) return listOfNumbers.indexOf(numberInMiddle);
            if (numberToGetIndex < numberInMiddle) high = middleIndex - 1;
            if (numberToGetIndex > numberInMiddle) low = middleIndex + 1;
        }
        return  -1;
    }
```
## Morning Planning
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
## Review
