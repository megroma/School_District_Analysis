# School District Analysis
## Overview
The school board has asked Maria to prepare and report the standardized test results of the district to look for trends to assist in the decision making. It was discovered that one school, Thomas High School, had possible academic dishonesty among its ninth graders. In order to have the most accurate results to present the analysis wad completed after removing the scores from this 9th grade class. The comparison of these results is described below. 
## Results
- How is district summary affected?
When each of the numbers are rounded to the tenths place, the average math and reading score changes were less than enough to affect the results. However, there were slight changes in the other values as shown by the following graphics. 

    Before THS 9th graders were removed:
![District_summary_pre](https://user-images.githubusercontent.com/90511014/141719870-d3b5bb78-31be-4f54-92e6-03583535ec0c.png)
    After THS 9th Graders were removed:
![district_summary_post](https://user-images.githubusercontent.com/90511014/141719890-ff818fd8-5397-47f0-a8f5-233be0f3ec2c.png)
- How is school Summary Affected?
Thomas Highschool is the only school that had affected scores. As such the School Summary was only different for Thomas High School. As shown by the images below.

    Before THS 9th graders were removed:
![THS_Pre](https://user-images.githubusercontent.com/90511014/141720231-4b274ae8-08e1-4d21-8bfa-4984507446ab.png)

    After THS 9th Graders were removed:
![THS_Post](https://user-images.githubusercontent.com/90511014/141720240-c089ec47-4418-4cf5-999f-62679dad6a6c.png)
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High School is still in second place however by a much smaller margin.

    Before THS 9th graders were removed:
![Top_3_pre](https://user-images.githubusercontent.com/90511014/141720272-aeae5081-1f7c-4145-8130-e1dafe5f14a1.png)

    After THS 9th Graders were removed:
![Top_3_post](https://user-images.githubusercontent.com/90511014/141720280-3fb1933e-2528-4b55-a3ac-63e893f7f103.png)
- How does replacing the ninth-grade scores affect the following
    - Math and reading scores by grade
    The Math and Reading grades all remained the same except for Thomas High School's 9th graders which are nan due to being corrupted. Below are the Math results however the reading scores had similar changes. 
    
        Before THS 9th graders were removed:
     ![Math_By_grade_pre](https://user-images.githubusercontent.com/90511014/141720318-a3274919-e0c5-4063-a6af-eaf5d1d7b9b5.png)
    
        After THS 9th Graders were removed:
     ![Math_By_Grade_post](https://user-images.githubusercontent.com/90511014/141720310-02de24cb-d5ef-4fb1-849c-1f64c95a0689.png)
    - Scores by school spending
    Scores by school spending are not perceptible when rounding. However, when looking at the numbers which are not as rounded there is a slight change in group that spends $630-644 per student.
    
        Before THS 9th graders were removed:
![Spending_Pre](https://user-images.githubusercontent.com/90511014/141720377-870be4fb-1dd9-4156-b8f4-73abd9c1ab35.png)
    
        After THS 9th Graders were removed:
![Spending_post](https://user-images.githubusercontent.com/90511014/141720381-f92173b2-540c-4c53-a7c8-dc4ffb1e3a2c.png)
    - Scores by school size
    Scores by size are also not perceptible when rounding. However as before when looking at the results that are not rounding there is a slight difference in the schools that have between 1000-2000 students. 
    
        Before THS 9th graders were removed:
![Size_pre](https://user-images.githubusercontent.com/90511014/141720401-2266c23a-b216-4430-a717-c02bd3319235.png)
   
        After THS 9th Graders were removed:
   ![Size_post](https://user-images.githubusercontent.com/90511014/141720407-e107e01c-0ca8-4c21-8546-eb50ddafa6fd.png)
    
   - Once again, the scores by school type were not perceptible when rounding. However, there is a slight difference with the charter schools.
    
        Before THS 9th graders were removed:
![Type_pre](https://user-images.githubusercontent.com/90511014/141720421-26e8131c-2db3-4849-bb53-8d19964f8402.png)
    
        After THS 9th Graders were removed:
   ![Type_post](https://user-images.githubusercontent.com/90511014/141720452-eef79fff-2b7d-4d1d-b215-358ac8783e02.png)

## Summary
As stated, the changes in rounded values were mostly not perceptible this is due to only 461 9th grades at Thomas High School compared to the 39170 total students. This affected data is only 1.2% of the total which explains why it is not as much of a change. However overall, the update scores are lower without the Thomas High School 9th Grade scores. Some of these changes are described below. 
1. The district summary had some of the largest changes. Percent passing math dropped from 75.0 to 74.8. % Passing Reading dropped from 85.8 to 85.7. % Overall passing dropped from 65.2 to 64.9. The largest change was for the %Overall passing which dropped 0.3%. However even with this being the largest change it was only .46% change which is not very much for it being the largest change. 
2. Thomas High School is still the school in the second place however it went from having a 0.35% lead over Griffin High School to only having a 0.03% lead. Thomas High School should keep this in mind if they are wanting to keep their standing in the future. 
3. As Thomas High School spends $638 per student only the range between 630 and 644 was affected. Each of the values were affected however % Overall Passing dropped from 62.85766 to 62.77823. This dropped about 0.079. This is only 0.13% drop which is not significant. 
4. As Thomas High School has 1635 students only the medium size 1000-2000 scores were affected the % Overall Passing dropped from 90.948012 to 90.557997. This is a difference of 0.39. This is a 0.42% change. 

