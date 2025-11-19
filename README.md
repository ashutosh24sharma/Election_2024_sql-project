# LOK SABHA ELECTION 2024 – SQL DATA ANALYSIS PROJECT


This project performs a comprehensive SQL-based analysis of the Indian Lok Sabha Elections 2024 dataset using SQL Server .
I ingested, cleaned, and transformed election result data, created party alliance classifications (NDA, I.N.D.I.A, OTHER), and calculated key performance insights across constituencies and states.

The analysis covers alliance-wise performance, state-wise trends, constituency-level winners and runners-up, EVM/postal vote breakdowns, and high-level election outcome metrics.

📊 KPIs & Analytical Insights
1. Total Seats

Total parliamentary constituencies available in the dataset.

2. Total Seats Available for Election Result

Unique constituencies with election results recorded.

3. Total Seats Won by NDA Alliance

Overall performance of the NDA coalition in the 2024 election.

4. Seats Won by Individual NDA Alliance Parties

Breakdown of seat wins for each party under the NDA umbrella.

5. Total Seats Won by I.N.D.I.A Alliance

Overall performance of the I.N.D.I.A coalition.

6. Seats Won by Individual I.N.D.I.A Alliance Parties

Seat distribution among different parties within I.N.D.I.A.

7. Added Party Alliance Column (NDA / I.N.D.I.A / OTHER)

Using SQL CASE logic, a new column was added to classify each party into its alliance group.

8. Alliance with Maximum Seats (NDA vs I.N.D.I.A vs OTHER)

National-level comparison to determine which alliance secured the most seats.

9. Winning Candidate Details (per State & Constituency)

Candidate Name

Party

Total Votes

Margin of Victory

10. State-wise Seats Won by Each Alliance

A detailed alliance breakdown for every state in India for the 2024 elections.

11. Top 10 Candidates with Highest EVM Votes

Ranking of candidates who received the most EVM votes nationwide.

12. Winner & Runner-up for Each Constituency (State-wise)

A structured view showing:

Winner

Runner-up

Party

Votes

Margin

13. Uttar Pradesh Election Summary

For India’s largest state by seats:

Total Seats

Total Candidates

Total Parties

Total Votes (EVM + Postal)

Separate EVM Votes

Separate Postal Votes

🛠️ Technologies Used

SQL Server (T-SQL)

Joins, Aggregations, CTEs

Window Functions (RANK, ROW_NUMBER, LAG, LEAD)

CASE Expressions

Views for repeatable reporting

Data cleaning & transformation queries

![PowerBI Dashboard]()
