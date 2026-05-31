<h1 align="center"><a href="https://github.com/scoliossis">github.com/scoliossis</a></h1>

```java
public class Main {
    static void main() {
        IO.println("Java 25 is so nice I use it all the time!!! bye bye public static void main(String[] args)");
        IO.println("I larp using latest java and have never actually used Java 25 which has this cuter print function");
        IO.println("I format code weird perhaps");
        IO.println("I cried when I found out IO.printf doesn't exist.");
        IO.println("I've done WAY too much markdown in my time, so I decided this readme should be in java!");

        for (AboutMe me : AboutMe.values()) System.out.printf("%s: %s\n", me.name(), me.description);
    }

    @AllArgsConstructor // hail lombok
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
