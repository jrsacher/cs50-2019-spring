# CSCI E-50 Spring 2019

***

## Section 4

### C ya later!

[Slides](https://docs.google.com/presentation/d/15irxsSaR153HbkBpnNTbX4G4dO9Fb-4rvDbQMCzw6Kg/edit?usp=sharing)

[Sandbox](http://bit.ly/2SQdDkQ)

[Attendance](https://docs.google.com/forms/d/e/1FAIpQLSewsRdowBnb7rt9i-VACLjpardY7kUo6Xvq8Cq0XDe1jYwKsA/viewform?usp=sf_link)

***

## Section 3 part 2

[Attendance](https://docs.google.com/forms/d/e/1FAIpQLSf725jcJcc9VqzuPmzmdUx8CCBUOCNGq8Ppr1wsriPqdoCevw/viewform?usp=sf_link)

***

## Section 3

### What’s the point(er)?

```C
int main(int argc, char *argv[])
{
    char *name = "section";
    
    if (argc == 2)
    {
        name = argv[1];
    }

    printf("Hello, %s!\n", name);
}
```

[Slides](https://docs.google.com/presentation/d/15KseYAGGgPp9MuThNyhcCEWbYNDFOzcvUKZW2KSw60I/edit?usp=sharing)

[Sandbox](http://bit.ly/2tyIMPs)

[Attendance](https://docs.google.com/forms/d/e/1FAIpQLScxgwxd3X_XjBy2BsHBDkGI2K2YJOvt5uP3Iicg3xHyi4IirQ/viewform?usp=sf_link)

***

## Section 2

### Arrays are awesome

```C
int main(void)
{
    string s = "Hello, section!";
    for (int i = 0, len = strlen(s); i < len; i++)
    {
        printf("%c\n", s[i]);
    }
}
```

[Slides](https://docs.google.com/presentation/d/1hctnYNQlqztHs8Xu4FXwrAmctZ1X7-XDuGBp5C3YkQk/edit?usp=sharing)

[Sandbox](http://bit.ly/2S92c7w)

[Attendance](https://docs.google.com/forms/d/e/1FAIpQLScB8yba6sMvsY1aItvE5n-8fwmQxLP9WfgJNNZgO5erzr-Cdw/viewform?usp=sf_link)

***

## Section 1

### From [**C**olorful **C**ats](https://scratch.mit.edu) to plain old `C`

```C
int main(void)
{
    printf("Hello, section!");
}
```

[Slides](https://docs.google.com/presentation/d/1-cHEmUAWGQ6z9_lM5xYrmzClZ4aGNXc9pz8Zy8IxYQw/edit?usp=sharing) for today's section

[Sandbox](http://bit.ly/2GxHVGA) for section 1

[Attendance](https://docs.google.com/forms/d/e/1FAIpQLSd4skycpQnoi8WfxsyrSehdJ_jG9a3u_sSUyfmTFpmlWO3M6Q/viewform?usp=sf_link)

#### Resources

* [CS50 Resource Guide](https://cs50.harvard.edu/extension/2019/spring/guide.pdf): A wonderful summary, thanks to [Emily Hong](https://cdn.cs50.net/2018/fall/video_projects/staff_gifs/gifs/Emily-Hong.gif)
* [CS50 Reference](https://reference.cs50.net/): A simplified guide to `C` functions
* [Discourse](https://discourse.cs50.net/c/cs50-2019-spring): the best place to get answers asynchronously
* [Reference sheets](https://drive.google.com/open?id=1WgsqoeDJ4v3ywVF8LqtUXE0KS0tEO4vU): A series of one-pagers on various topics
* [CS50 Shorts](https://www.youtube.com/playlist?list=PLhQjrBD2T381k8ul4WQ8SQ165XqY149WW): Short videos on specific topics

[Contact Josh](mailto:cs50@jrsacher.com)

Learn more about Josh by [googling](https://www.google.com/search?q=Joshua+Sacher) (I'm not the crossfit guy, so pretty much anyone that looks out of shape is me)
