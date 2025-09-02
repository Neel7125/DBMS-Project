# Electronic Election Management System

## 📌 Overview
This project implements an **Electronic Election Management System (EEMS)** titled **E-Vote**, designed as part of our DBMS coursework.The system leverages database management techniques to streamline electoral processes including **voter registration, candidate management, voting, and result tabulation**. Our focus is on ensuring **transparency, efficiency, accessibility, and security** in elections.

## 🎯 Objectives
- Develop a robust database system to manage the **entire election lifecycle**.
- Facilitate **voter and candidate registration** with full details.
- Implement **secure voting and result aggregation**.
- Provide **report generation and analytics** for voters, candidates, and administrators.
- Ensure **scalability, usability, and regulatory compliance**.

## 👥 Users
1. **Surfer (Unlogged User)**
   - Search and view candidate/party details.
   - Compare candidates and their platforms.

2. **Voter**
   - Register / Modify profile.
   - Search candidates by name, party, or position.
   - Maintain voting choices and submit vote.
   - Rate candidates and leave feedback.
   - View election reports and results.

3. **Candidate**
   - Register / Modify profile.
   - Add campaign details (slogans, promises, events).
   - View reports (performance, competitor analysis).
   - Track campaign progress.

4. **Administrator**
   - Manage elections, candidates, and voters.
   - Oversee voting process and result tabulation.
   - Generate global reports/statistics.

## 📊 Features
- **Candidate Management**: Registration, campaign details, and updates.
- **Voter Management**: Secure registration and voting.
- **Voting System**: Submit and confirm votes with acknowledgement.
- **Reporting & Analytics**:
  - Candidate/party comparison.
  - Voting history & choices.
  - Election statistics and summaries.
  - Financial ledger of campaigns.
  - Candidate-wise and party-wise performance reports.
- **Transparency & Fairness**: Safeguards voter information and ensures accountability.

## 🛠️ Implementation
- **Database Design**:
  - Entities: `Voters`, `Candidates`, `Parties`, `Elections`, `Votes`, `Campaigns`, etc.
  - Relationships modeled via **ERD → Relational Schema**.
  - Use of **M–N relations** and **composite primary keys**.
- **Queries Implemented**:
  - Candidate/party search and comparison.
  - Voter feedback and ratings.
  - Election result tabulation.
  - Campaign progress tracking.
- **Tools Used**:
  - PostgreSQL 
  - SQL (DDL, DML, Joins, Aggregations).
  - Normalization up to 3NF.
  - Reporting via SQL queries.
 
## 🏆 Initiative
Our initiative is to make elections **easier, fairer, and transparent** using technology.  
We designed this system to ensure **every vote counts**, election authorities can **manage seamlessly**, and **citizens trust the process**.

