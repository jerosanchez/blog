# 35 habits of a good programmer

#career

Learning to code is easy. Being a good programmer is another story. I share some of the habits that you must internalize if you want to program in a professional way.

! [Cup of coffee](https://images.unsplash.com/photo-1497515114629-f71d768fd07c?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=2000&fit=max&ixid=eyJhcHBfaWczfQN)

---

I have a huge _backlog_ of talks to watch from the last WWDC. As things are, I doubt that I will have time to see everything I want to see before the next conference... too much to bite! Anyway, the point is that I found one of the last videos veri interesting, [Great Developer Habits - WWDC 2019](https://developer.apple.com/videos/play/wwdc2019/239/), and as I was taking notes I thought that they very well served as a declaration of intent and guide for the blog.

So I share with you these ideas to become a good programmer. As is logical, coming from a WWDC, some points are very directed to those of us who use Xcode as a daily workhorse, but there is also deep wisdom that can be used by anyone who debotes his life to this noble profession of writing code.

Articles will surely drop to delve into many of these ideas 😉

## Organize

1. Organize files in groups according to their function
2. Replicate the structure of your project following the file structure
3. Divide the _storyboards_ that are very large
4. Update your project when there are changes in Xcode or Swift
5. Eliminate the commented out code (that's what version control is for)
6. Attack the root cause of _warnings_ and make them go away

## Control [changes]

7. Use version control
8. Keep commits small and affecting isolated parts of the code
9. Write commit messages that are useful
10. Use a branch for each fix and new feature

## Documents

11. Add comments that provide context and explains the why of things
12. Use variable and constant names that are descriptive
13. Include documentation (press `Opt` + ` Cmd` + `/`)

## Do tests

14. Write unit tests
15. Run unit tests before pushing changes
16. Implement an infrastructure for continuous integration

## Analyze

17. Simulate poor network connections with Network Link Conditioner
18. Use sanitizers and checkers
19. Measure performance and efficiency with Debug Gauges
20. Investigate problems with Instruments

## Evaluate

21. Make code reviews a part of your routine
22. Understand each modified line
23. Compile the entire project
24. Run the tests
25. Check the style, writing and syntax used

## Decouple

26. Identify functional areas and separate them
27. Use packages (SPM is already available in Xcode 11)
28. Make your work scalable between different applications
29. Improve efficiency using extensions
30. Share with others what may be useful
31. Add good documentation to your packages

## Manage

32. Use open source and the work of the community [responsibly](https://programadorartesano.com/lidiando-con-las-dependencias-externas/)
33. Thoroughly understand the dependencies you add
34. Make sure that everything you add respects privacy
35. Have a plan ready in case any dependency disappears or stops being maintained
