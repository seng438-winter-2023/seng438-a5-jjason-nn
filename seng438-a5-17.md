**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:17    |     
| -------------- |
| Student Names: |    
| Ajay Arumugam  |     
| Haseeb Khan    |     
| Sadia Khandaker|
| Jason Nguyen   |

# Introduction

In this lab, we used reliability assessment tools to look at integration test data. We did this by using two ways to look at failure data: reliability growth testing and the Reliability Demonstration Chart (RDC). By changing the failure data, we were able to make models and charts that helped us figure out the Mean Time to Failure (MTTF), the number of failures, and how reliable the software was. The lab's main objective was to enhance our understanding of reliability analysis, measurement, and certification, as well as to establish when testing is necessary in software development. Moreover, we were exposed to the notion of failure data and its critical significance in avoiding future failures. The lab also helped to clarify our theoretical grasp of the relevance of reliability testing in software testing techniques. Lastly, we looked at tools that aid in the visualization and decision-making of failure data, such as reliability growth testing and RDC. Reliability growth testing required several tools and models to refine, analyze, and forecast data, while RDC created a visual and comprehensive graph for decision-making with fewer tools and models.

# Assessment Using Reliability Growth Testing 

## Result of Model Comparison (Selecting Top Two Models)


## Result of Range Analysis (An Explanation of Which Part of Data Is Good for Proceeding With the Analysis)


## Plots for Failure Rate and Reliability of the SUT for the Test Data

## Discussion of Decision Making Given a Target Failure Rate


## Discussion of the Advantages and Disadvantages of Reliability Growth Analysis

Reliability growth analysis is a useful tool for analyzing the reliability of a system under test (SUT), and it has both advantages and disadvantages.

**Advantages:**
- One of the main advantages of reliability growth analysis is that it provides insight into how the software's reliability evolves over time. Developers can see whether the software's reliability is increasing or decreasing, allowing them to make more informed decisions regarding software development and maintenance.
- Using the graphs produced by a reliability growth analysis, which depicts any time-dependent trends, we can make decisions based on the past behaviour of our data and predict its future behaviour.
- The results of reliability growth analysis make it simple to identify and examine changes at a specific point in time, assisting developers in identifying and examining the impact of those changes on the project's development.

**Disadvantages:**
- To be accurate, reliability growth analysis necessitates a large amount of failure data. In the absence of sufficient failure data, the analysis may not provide an accurate depiction of the system's reliability, leading to erroneous decisions.
- Reliability growth analysis makes the assumption that, apart from changes brought on by failure correction, the system in which the failures were discovered changes very little or not at all. Unreported failures or major changes to the program might lead to incorrect failure statistics, meaningless insights, or poor decisions.
- The process of making the graphs required for reliability growth analysis is often tedious and time-consuming. It can also be confusing and require extensive knowledge to produce reliable results, particularly when using multiple tools with the same data.
- The prediction models used in reliability growth analysis can differ depending on the mathematical functions used to determine the system's target failure, resulting in different results for different models.


# Assessment Using Reliability Demonstration Chart 

## 3 Plots for MTTFMin, Twice and Half of It for Your Test Data

## Explain Your Evaluation and Justification of How You Decide The MTTFmin

## Discussion of the Advantages and Disadvantages of Reliability Demonstration Chart (RDC)

A Reliability Demonstration Chart (RDC) is a graphical tool used to assess a system's reliability. It has the following advantages and disadvantages:

**Advantages:**
- RDC is an easy way to assess system reliability. The ease of assembling a spreadsheet or locating a tool for plotting test data to determine the performance of the system under test (SUT) over time is one of the benefits of RDC. In addition, generating and analyzing the plots does not require a significant amount of time, making this method of determining system reliability efficient.
- The RDC graphs are visually intuitive and allow developers to identify SUT reliability trends with relative ease.

**Disadvantages:**
- The reliability of a system cannot be quantified using RDC. As a result, it may be difficult for developers to make decisions or draw conclusions about the system's overall reliability. Although RDC plots are useful for seeing patterns in reliability, they do not provide a precise metric for assessing the reliability of the system.
- Another limitation of RDC is the difficulty in calculating the Mean Time to Failure (MTTF), which can be both time-consuming and difficult. A meticulous analysis of the data and a series of calculations are required to determine the appropriate MTTF value. It can be difficult to determine the most appropriate value when there is insufficient information. This process can be tedious and necessitates a significant investment of time and resources.


# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself

The lab would have been improved if the instructions had been clearer and more comprehensive, as our group was unsure of the intended objectives and methodology. In addition, we encountered significant challenges in completing the lab due to the compatibility issues associated with different operating systems. This issue was exacerbated by the fact that the software we had to use was extremely outdated, making it incompatible with modern operating systems. Future lab assignments should take into account the diverse operating systems of students and provide clear, concise, and thorough instructions in order to maximize their effectiveness and foster a deeper understanding of the concepts being taught.
