# Interview-Intel: Interview Intelligence System

## Project Overview

**Interview-Intel** is an advanced tool designed to improve the hiring process by analyzing interview conversations. The tool records, transcribes, and analyzes candidate interviews, providing recruiters and HR managers with detailed insights into the interview dynamics. By harmonizing all aspects of the interview process, it aims to reduce bias, improve feedback loops, and enhance overall recruitment efficiency.

This system predicts the status of the interviews, allowing recruiters to check the sanity of the interview and assess if the interview was biased based on various factors such as speaking pace, monologue durations, silence ratio, late joining time, and more.

---

## Dataset Description

The dataset used for this project contains information about interviews, candidates, and interviewers. Below are the key features:

### Key Features:

- **Interview Id**: ID of the interview
- **Candidate Id**: ID of the candidate
- **Interviewer Id**: ID of the interviewer
- **Profile**: Type of profile for the candidate
- **S.L.R.C (Speak to Listen Ratio Candidate)**: Ratio of speaking time to listening time for the candidate
- **S.L.R.I (Speak to Listen Ratio Interviewer)**: Ratio of speaking time to listening time for the interviewer
- **A.T.T (Avg Turn Time)**: Average time for interactions between the interviewer and candidate
- **L.M.I (Longest Monologue Interviewer)**: Longest uninterrupted speaking time of the interviewer
- **L.M.C (Longest Monologue Candidate)**: Longest uninterrupted speaking time of the candidate
- **S.R (Silence Ratio)**: Percentage of time when no one was speaking
- **L.J.T.C (Late Joining Time Candidate)**: Time the candidate joined late
- **L.J.T.I (Late Joining Time Interviewer)**: Time the interviewer joined late
- **N.I.C (Noise Index Candidate)**: Percentage of background noise on the candidate side
- **N.I.I (Noise Index Interviewer)**: Percentage of background noise on the interviewer side
- **S.P.I (Speaking Pace Interviewer)**: Average number of words spoken per minute by the interviewer
- **S.P.C (Speaking Pace Candidate)**: Average number of words spoken per minute by the candidate
- **L.A.I (Live Absence Interviewer)**: Percentage of time the interviewer was absent from the video call
- **L.A.C (Live Absence Candidate)**: Percentage of time the candidate was absent from the video call
- **Q.A (Questions Asked)**: Total number of questions asked during the interview
- **P.E.I (Perceived Emotion Interviewer)**: Emotion of the interviewer (Positive/Negative)
- **P.E.C (Perceived Emotion Candidate)**: Emotion of the candidate (Positive/Negative)
- **Compliance Ratio**: Ratio of questions assigned vs. questions actually asked
- **Interview Duration**: Duration of the interview
- **Interview Intro**: Whether the interviewer introduced themselves
- **Candidate Intro**: Whether the candidate introduced themselves
- **Opp to Ask**: Whether the candidate was given an opportunity to ask questions
- **Status**: The status of the candidate (Selected/Rejected)

---

![Interview-Intel Workflow](attachment:1ea0f0ad-364a-4510-8b66-1e000569fb7c.png)

## Conclusion

- The data indicates a relatively high number of candidates being actively considered for the job, with **486 individuals qualifying for consideration**.
- An additional **400 candidates** fall into the "may consider" category, suggesting that they possess some qualifications but may require further evaluation.
- However, **314 candidates** have been marked as "not considered," indicating they do not meet the necessary criteria for the role.

---

## Analysis or Insights

- There were more job openings for **Program Managers** and fewer for the **Marketing** department.
- Candidates were predominantly considered for the **Program Manager** role compared to other profiles.
- **Developer** candidates were more likely to be rejected, while candidates from the **Sales** profile had the least rejection rate.
- Candidates for the **Automation** profile were often placed in the "not selected" pool or kept on hold for further evaluation.

---

## Prescriptive Analysis

Based on the above insights, the following actions are recommended:

1. **Automation Profile Adjustment**:
   - With a large number of candidates applying for the **Automation** profile, the client may need to either increase the number of teams or expand the scope of projects.
   
2. **Improved Candidate Sorting**:
   - Implement a better approach to sort candidates by:
     - Summarizing the **Job Description**, including only the essential skill sets, roles, and responsibilities.
     - Conducting an **assessment round** for technical profiles or where certain skill sets are mandatory.
   
   This will help streamline the interview process and reduce the time HR spends evaluating candidates, improving the overall efficiency of the recruitment process.

---![image](https://github.com/user-attachments/assets/95da5658-de1d-47bc-903b-3c1224efa378)



### Next Steps:

- **Feature Engineering**: Investigate additional features that may improve the model’s predictive capability.
- **Model Evaluation**: Perform further evaluation of the prediction model to determine the most significant indicators of a candidate's success in interviews.
- **Scalability**: Explore ways to scale the tool for large recruitment drives.
