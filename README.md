<h1 align="center"><a href="https://github.com/scoliossis">github.com/scoliossis</a></h1>

```java
public class Scale extends Human {
    public Scale() {
        this.twitter = "https://x.com/scoliosissy";
        this.youtube = "https://www.youtube.com/@scoliosissy";
        this.info = """
            I larp using latest java which has this cuter print function
            I format code weird perhaps
            I've done WAY too much markdown in my time, so I decided this readme should be in java!
            I cried when I found out IO.printf doesn't exist.
        """;
        
        IO.println("Scale initialised: " + this.info);
        for (AboutMe me : AboutMe.values()) System.out.printf("%s: %s\n", me.name(), me.description);
    }

    @AllArgsConstructor // dttm if you dont use lombok
    public enum AboutMe {
        JAVA_FAN("i LOVE java and if it were possibly i would marry it, however, it seems we live in a world where im incappable of doing so."),
        AI_HATER("NONE of my projects use ANY AI"),
        LIAR("the above point is actually a LIE, AI is used here to copy all the easings.net functions into a java enum: https://github.com/scoliossis/ScaleHackV3/blob/master/src/main/java/com/github/scoliossis/utils/render/EasingUtil.java#L8"),
        KAWAII("fan of cute readme's"),
        HASNT_SHOWERED_BEFORE("scoliosissy on discord"),
        NEED_MORE_DOMAINS("https://dragonwarriorp.ee/");

        public final String description;
    }
}
```
