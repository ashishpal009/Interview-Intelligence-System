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
[image.png](attachment:1ea0f0ad-364a-4510-8b66-1e000569fb7c.png)
