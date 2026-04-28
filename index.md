---
# Do not edit the text between these lines!
layout: default
---

# COMP110 Data Analysis: Video-Based Learning

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="{{site.baseurl}}/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>





## Overview

This project analyzes whether increasing video-based resources—specifically walkthroughs of common mistakes—would improve student learning in COMP110.

The analysis uses anonymized survey data to explore relationships between:
- Lesson video effectiveness (`ls_effective`)
- Student understanding (`understanding`)
- Perceived course value (`valuable`)

---

## Data Analysis

To begin, I examined how students rated the effectiveness of lesson videos.

![Video Effectiveness Distribution]({{ site.baseurl }}/static/imgs/plot1.png)

The distribution shows that most students rate lesson videos positively, with responses concentrated toward the higher end of the scale.

---

Next, I analyzed the relationship between video effectiveness and student understanding using a heatmap to better capture density in discrete data.

![Heatmap]({{ site.baseurl }}/static/imgs/plot2.png)

This visualization shows that higher video effectiveness ratings tend to align with higher reported understanding. However, the relationship is not perfectly linear and shows variability.

---

Finally, I examined how perceived course value varies with video effectiveness using a boxplot.

![Boxplot]({{ site.baseurl }}/static/imgs/plot3.png)

Students who rate videos as more effective also tend to report higher course value, suggesting a positive association between video resources and perceived learning outcomes.

---

## Conclusion

The analysis suggests a positive relationship between students’ perceptions of video effectiveness and both their understanding and perceived course value. However, because all variables are self-reported, this relationship does not establish causation.

It is unclear whether videos directly improve learning, or if students who are already more confident tend to rate all aspects of the course more positively.

---

## Recommendations

Rather than immediately expanding video content, a more effective approach would be to:

- Introduce targeted walkthrough videos for common mistakes on select assignments  
- Collect data on student engagement with these videos  
- Measure whether they reduce confusion or improve understanding  

This experimental approach would provide stronger evidence for whether expanding video resources creates meaningful value.

---

## Trade-offs and Considerations

- Producing additional videos requires time and effort from instructional staff  
- Over-reliance on videos may reduce engagement with other learning methods  
- Not all students prefer video-based learning  

---

## Final Reflection

While video resources appear valuable, the current data is insufficient to justify expanding them without further testing. A targeted, data driven experiment would be the most effective next step.