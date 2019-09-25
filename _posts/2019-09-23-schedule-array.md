---
layout: post
name: "Schedule Array"
author: "Lemuel De Los Santos"
---

**Q. What was my program supposed to do?**  
**A.** We were supposed to make a schedule of the week, and we used [Louis'](mailto:louisg9601@afsenyc.org) schedule.

**Q. How did the program work?**  
**A.** Yes, we have the weekdays displayed side by side.

**Q. What problems/challenges were discovered?**  
**A.** I guess we didn't have enough time to complete the whole thing.

**Q. How were the problems/challenges handled?**  
**A.** We completed it days after, and It works great now.

**Q. Show text or a screenshot of a section of code (not the whole program) that is supposed to do something and explain what it does.**  
**A.** Sample code of `script.js`
```js
// Loop through each day in the schedule
for (int i = 0; i < schedule.length; i++) {
  // Color in day with designated color
  fill(...colors[i]);

  // Loop through each period in the day
  string day = schedule[i];
  day.forEach((period, j) => text(period, i * 300 + 20, j * 40 + 80));
}
```
In this code sample, It show a `for` loop, which loops through the schedule, getting each day.
And in each day, it loops through using `forEach`, and gets all periods.
It then displays the periods using the `text` function.


> [Result](https://schedule-array-lemueld6200.glitch.me)
