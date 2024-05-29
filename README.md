# Call Center Scorecard Project

## Introduction
The call center scorecard project was implemented to evaluate agent productivity and fairly calculate bonuses based on their performance. This system allows for detailed analysis of key metrics and provides a transparent mechanism for additional compensation.

## Scorecard Description
The scorecard consists of several key sections:

### Agent Productivity
- **Average Talk Time**: The average conversation time is 00:06:25, earning 16.66 points.
- **Average Hold Time**: The average hold time is 00:01:08, earning 14.50 points, rated as "Highly Effective".
- **Average ACW Time**: The average after-call work time is 00:00:09, earning 16.66 points.
- **CPH (Calls Per Hour)**: The number of calls handled per hour is 4.58, earning 14.50 points, rated as "Highly Effective".

### Administrative Score
- **Attendance**: The agent's attendance percentage is 100%, earning 16.66 points.
- **Acc Dispositioning Total Calls**: The total number of properly disposed calls is 0, earning 16.66 points.

### Total Scorecard Score
The total scorecard score is 95.60 points out of a maximum of 100, rated as "Highly Effective".

### Total Bonus
The total bonus is calculated using the agent's total score multiplied by the eligibility factor and divided by the number of months with a score. For the score of 95.60, the total bonus is $100.93.

## Metric Definitions and Calculations
### Productivity Metrics
- **Average Talk Time**: Calculated by summing the total conversation time and dividing by the number of calls.
- **Average Hold Time**: Calculated by summing the total hold time and dividing by the number of calls.
- **Average ACW Time**: Calculated by summing the total after-call work time and dividing by the number of calls.
- **CPH (Calls Per Hour)**: Calculated by dividing the total number of calls handled by the total number of hours worked.

### Administrative Metrics
- **Attendance**: Calculated as the percentage of days worked over the total number of working days.
- **Acc Dispositioning Total Calls**: Total number of properly disposed calls.

## Evaluation and Classification Criteria
- **Metric Points**: Each metric has a maximum of 16.66 points.
- **Rating Ranges**: "Outstanding" for 16.66 points, "Highly Effective" for 14.50 points.
- **Maximum and Total Score**: Points earned in each metric are summed to get the total score.

## Bonus Calculation
The total bonus is calculated using the agent's total score multiplied by the eligibility factor and divided by the number of months with a score.

## Tools and Technologies Used
The scorecard was developed using Power BI, integrating data from various sources of the call center's CRM system.

## Results and Benefits
Since the implementation of the scorecard, a 20% improvement in agent productivity has been observed, along with greater transparency in bonus payments.

## Conclusions and Recommendations
The scorecard has proven to be an effective tool for measuring and improving agent performance. It is recommended to continue refining the metrics and explore the integration of new data sources for a more comprehensive analysis.

## Scoring Data
The scoring data file contains information about the metrics and scores of the agents.

### Data Examples

| Indicator           | Agent Group | Interval Start | Interval End | Point | Rating     | Letter | Target | MaxPoint |
|---------------------|-------------|----------------|--------------|-------|------------|--------|--------|----------|
| Total Score Point   | CES         | 99.9           | 100          | 100.0 | Outstanding| A      | 80.0   | 100.0    |
| Total Score Point   | LEAD        | 99.9           | 100          | 100.0 | Outstanding| A      | 80.0   | 100.0    |
| Total Score Point   | LES         | 99.9           | 100          | 100.0 | Outstanding| A      | 80.0   | 100.0    |
| Total Score Point   | NH          | 99.9           | 100          | 100.0 | Outstanding| A      | 80.0   | 100.0    |
| Total Score Point   | SES         | 99.9           | 100          | 100.0 | Outstanding| A      | 80.0   | 100.0    |

### Detailed Data Description
The data provides a detailed view of agent performance, categorizing them into different groups and assigning scores based on specific intervals. These scores are then used to determine agent classifications and calculate their bonuses.

- **Total Score Point**: This indicator shows the total score obtained by agents in different groups.
- **Agent Group**: Agents are categorized into groups such as CES, LEAD, LES, NH, SES.
- **Interval Start and End**: These intervals define the range in which the score is measured, in this case, from 99.9 to 100.
- **Point**: Points earned by agents in the specified interval.
- **Rating and Letter**: Classification and corresponding letter based on the points earned. For example, a score of 100.0 corresponds to an "Outstanding" rating with the letter "A".
- **Target**: The target that agents need to achieve.
- **MaxPoint**: Maximum possible score for the metric.

## Integration in Project Documentation
These data are used to evaluate agent performance across different metrics and categories. The following describes how these data are integrated into the evaluation and bonus calculation process.

### Evaluation Process

1. **Data Collection**: Performance data of agents are collected in specific intervals.
2. **Point Assignment**: Points are assigned to agents based on their performance compared to set targets.
3. **Classification**: Classifications are assigned to agents based on their total scores.
4. **Bonus Calculation**: Bonuses are calculated using total scores and assigned classifications.

This information helps maintain a transparent and fair evaluation process, ensuring agents are adequately rewarded for their performance.
