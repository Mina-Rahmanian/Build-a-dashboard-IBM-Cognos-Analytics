# IBM Cognos Analytics Visualization Assignment

## Overview

This project involves creating visualizations using IBM Cognos Analytics based on the dataset provided. The assignment includes creating three separate dashboards to analyze current technology usage, future technology trends, and demographics.

## Software Used

- **IBM Cognos Analytics** (Free Trial Version)

## Prerequisites

- Access to IBM Cognos Analytics
- Familiarity with basic navigation and visualization creation in IBM Cognos

## Dataset

- **Source**: [Stack Overflow 2019 Developer Survey Results](https://stackoverflow.blog/2019/04/09/the-2019-stack-overflow-developer-survey-results-are-in/)
- **Files Used**:
  - [m5_survey_data_demographics.csv]()
  - [m5_survey_data_technologies_normalised.csv]()

*Note: Use the modified subset of the dataset provided with this assignment.*

## Dashboard Instructions

### 1. Current Technology Usage Dashboard

**File**: `m5_survey_data_technologies_normalised.csv`

#### Panel 1: Top 10 Programming Languages Used
- **Type**: Bar Chart
- **Fields**: `LanguageWorkedWith` (X-Axis), Respondent Count (Y-Axis)
- **Features**: Show value labels, Color coding
- **Title**: "Top 10 Programming Languages Used"

#### Panel 2: Top 10 Databases Used
- **Type**: Column Chart
- **Fields**: `DatabaseWorkedWith` (X-Axis), Respondent Count (Y-Axis)
- **Features**: Show value labels, Color coding
- **Title**: "Top 10 Databases Used"

#### Panel 3: Platforms Used
- **Type**: Word Cloud
- **Fields**: `PlatformWorkedWith` (Words), Frequency (Size)
- **Features**: Color coding
- **Title**: "Platforms Used by Respondents"

#### Panel 4: Top 10 Web Frameworks Used
- **Type**: Hierarchy Bubble Chart
- **Fields**: `WebFrameWorkedWith` (Bubbles), Respondent Count (Size)
- **Features**: Color coding
- **Title**: "Top 10 Web Frameworks Used"

### 2. Future Technology Trend Dashboard

**File**: `m5_survey_data_technologies_normalised.csv`

#### Panel 1: Top 10 Programming Languages Desired Next Year
- **Type**: Bar Chart
- **Fields**: `LanguageDesireNextYear` (X-Axis), Respondent Count (Y-Axis)
- **Features**: Show value labels, Color coding
- **Title**: "Top 10 Programming Languages Desired Next Year"

#### Panel 2: Top 10 Databases Desired Next Year
- **Type**: Column Chart
- **Fields**: `DatabaseDesireNextYear` (X-Axis), Respondent Count (Y-Axis)
- **Features**: Show value labels, Color coding
- **Title**: "Top 10 Databases Desired Next Year"

#### Panel 3: Platforms Desired Next Year
- **Type**: Tree Map
- **Fields**: `PlatformDesireNextYear` (Area), Frequency (Size)
- **Features**: Contrast label color
- **Title**: "Platforms Desired Next Year"

#### Panel 4: Top 10 Web Frameworks Desired Next Year
- **Type**: Hierarchy Bubble Chart
- **Fields**: `WebFrameDesireNextYear` (Bubbles), Respondent Count (Size)
- **Features**: Color coding
- **Title**: "Top 10 Web Frameworks Desired Next Year"

### 3. Demographics Dashboard

**File**: `m5_survey_data_demographics.csv`

*Note: Apply filters to include only entries where `Gender` is 'Man' or 'Woman'.*

#### Panel 1: Respondent Count by Gender
- **Type**: Pie Chart
- **Fields**: `Gender` (Segments), Respondent Count (Size)
- **Features**: Display percentages
- **Title**: "Distribution of Respondents by Gender"

#### Panel 2: Respondent Count by Country
- **Type**: Map Chart
- **Fields**: `Country` (Regions-Locations), Respondent Count (Regions-Location Color)
- **Title**: "Respondent Count by Country"

#### Panel 3: Respondent Count by Age
- **Type**: Line Chart
- **Fields**: `Age` (X-Axis), Respondent Count (Y-Axis)
- **Features**: Show value labels, Show markers
- **Title**: "Respondent Count by Age"

#### Panel 4: Respondent Count by Gender and Education Level
- **Type**: Stacked Bar Chart
- **Fields**: `Gender` and `Formal Education Level` (Stacked Bars), Respondent Count (Length)
- **Features**: Show value labels
- **Title**: "Respondent Count by Gender and Formal Education Level"

## Getting Started

1. **Download the Dataset**: Obtain `m5_survey_data_demographics.csv` and `m5_survey_data_technologies_normalised.csv`.
2. **Upload Data to Cognos**: Load the CSV files as data assets in IBM Cognos Analytics.
3. **Create Dashboards**: Use the provided instructions to set up and configure each dashboard with the appropriate visualizations.
