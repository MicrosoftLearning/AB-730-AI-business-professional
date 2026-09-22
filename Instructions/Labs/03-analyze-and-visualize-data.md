---
lab:
    title: 'Analyze and visualize data with Microsoft Copilot'
    description: 'Use Copilot in Excel and the Analyst agent to find trends, analyze feedback, generate charts, and build formulas from a sales dataset.'
    duration: 20
    level: 100
    islab: true
    status: 'in-development'
    targetDate: '2027-03-01'
---

# Analyze and visualize data with Microsoft Copilot

## Scenario

In this exercise, you use Microsoft Copilot to analyze a quarterly sales dataset. You use Copilot in Excel to find trends, categorize customer feedback, and generate a chart, then use the Analyst agent to produce a deeper, shareable report from the same data.

By the end of this exercise, you'll be able to:

- Use Copilot in Excel to summarize trends and generate charts from a dataset.
- Analyze a text column for themes and sentiment using Copilot.
- Build a formula in natural language instead of writing it yourself.
- Use the Analyst agent to produce a deeper, shareable report from the same data.

This exercise should take approximately **20** minutes to complete.

> **Tip**: This exercise is about getting comfortable using Copilot in Excel, not following steps exactly. You're encouraged to try your own prompts instead of typing the examples exactly as written. If you'd rather use your own dataset, keep in mind the example prompts reference this exercise's column names (Region, Product, Quarter, UnitsSold, Revenue, CustomerFeedback), so you'll need to adjust them to match your data.

## Before you start

You need:

- A Microsoft 365 account with a Microsoft 365 Copilot license.
- Access to Excel on the web through [Microsoft 365](https://m365.cloud.microsoft.com) at `https://m365.cloud.microsoft.com` or through the desktop app.
- Access to Microsoft Copilot [Microsoft Copilot](https://copilot.cloud.microsoft) at `https://copilot.cloud.microsoft`
- The sample dataset for this exercise. Download [quarterly-sales-data.csv](https://raw.githubusercontent.com/MicrosoftLearning/AB-730-AI-business-professional/main/Allfiles/quarterly-sales-data.csv) from `https://raw.githubusercontent.com/MicrosoftLearning/AB-730-AI-business-professional/main/Allfiles/quarterly-sales-data.csv`. Press Ctrl+S to save the CSV file.

1. Open Excel and create a new blank workbook.

1. Import the data by opening the **Data** tab and selecting **Get Data** > **Get Data...** > **From Text/CSV**, then select **Upload file** and choose the `quarterly-sales-data.csv` file you downloaded.

1. Select **Next**.

1. In the **Preview file data** dialog that appears, leave the **File Origin**, **Delimiter**, and **Data Type Detection** settings at their defaults, then select **Transform data** to import the data as a table into a new worksheet.

1. Close the **Power Query Editor** and select **Save** to return to the main Excel window.

1. Save the workbook to OneDrive as `Quarterly Sales Analysis`.

1. Select the Copilot icon on the bottom right to open the Copilot pane, select the mode dropdown, and then choose **Allow editing** so Copilot can apply changes directly to your workbook.

> **Important**: Copilot in Excel can only work with files saved on OneDrive, and your data must be formatted as a table or a supported range. Keep **Allow editing** selected for the rest of this exercise, as Copilot applies changes, such as new sheets and charts, directly to your workbook instead of asking you to add them.

## Task 1: Find trends with Copilot in Excel

Your manager asked you to identify how sales are trending across regions and products before a leadership review.

1. In the Copilot pane, enter the following prompt:

    ```prompt
    Summarize total revenue by region and highlight the top-performing region. Create a new worksheet and add the summary to it.
    ```

1. Review the summary Copilot generates. Verify the summary has been added to a new sheet.

1. Return to the worksheet that contains the quarterly sales data. In the Copilot pane, enter the following prompt to explore the data further:

    ```prompt
    Compare units sold between Q1 and Q2 for each product. Create a new worksheet and add the comparison to it.
    ```

1. Review the comparison Copilot generates. Copilot adds the product comparison to a new sheet.

## Task 2: Analyze customer feedback

The dataset includes a column of written customer feedback. Instead of reading each comment individually, you'll ask Copilot to identify recurring themes.

1. Return to the worksheet that contains the quarterly sales data. In the Copilot pane, enter the following prompt:

    ```prompt
    Review the CustomerFeedback column and identify the major themes.
    ```

1. Review the themes Copilot identifies, such as comments about sizing, durability, or shipping. Copilot may add this analysis to a new sheet.

1. Select the quarterly sales data worksheet, then ask Copilot to label the sentiment of each comment:

    ```prompt
    Analyze the CustomerFeedback column and label each row by sentiment.
    ```

1. Review the new labeled column Copilot inserts.

> **Tip**: If the themes feel too broad, refine your prompt to focus on a specific product or region, such as "Identify themes in feedback for the SummitPeak Backpack only."

## Task 3: Generate a chart

Leadership wants a visual that's easy to scan during the review meeting.

1. In the Copilot pane, enter the following prompt:

    ```prompt
    Create a bar chart showing total revenue by region. Add it to a new worksheet.
    ```

1. Review the chart Copilot generates in the new worksheet.

1. Refine the chart with a follow-up prompt:

    ```prompt
    Add data labels and sort the regions from highest to lowest revenue.
    ```

1. Review the refined chart.

## Task 4: Build a formula with Copilot

You want to calculate the average revenue per unit sold for each row, without writing the formula yourself.

1. Select an empty column next to your data and select the first empty cell in that column.

1. In the Copilot pane, enter the following prompt:

    ```prompt
    Calculate the average revenue per unit sold for each row using the Revenue and UnitsSold columns.
    ```

1. Review the column. Copilot adds the formula for every row automatically since **Allow editing** is selected. 

1. Select **Done** when finished.

## Task 5: Generate a deeper report with the Analyst agent

Your manager also wants a polished report that goes beyond a quick summary, including trends and recommendations you can share with the wider team.

1. Open Microsoft Copilot at [Microsoft Copilot](https://copilot.cloud.microsoft) at `https://copilot.cloud.microsoft`.

1. In the left navigation pane, select **Analyst** from the list of Pinned agents.

1. Select the **+** icon and attach your `Quarterly Sales Analysis` Excel workbook from OneDrive.

1. Enter the following prompt:

    ```prompt
    Highlight key trends in revenue and units sold by region and product between Q1 and Q2. Identify any regions or products with declining revenue or units sold, or negative customer feedback themes. Include supporting charts or tables.
    ```

1. Review the report the Analyst agent generates, including any charts or tables.

1. Ask a follow-up question to refine the analysis:

    ```prompt
    Which product had the most negative customer feedback themes, and how does that align with its sales trend?
    ```

1. Ask the agent to prepare the output for your audience:

    ```prompt
    Summarize these findings into three bullet points for a leadership slide.
    ```

## Summary

In this exercise, you used Copilot in Excel to explore and visualize a dataset, and the Analyst agent to turn that same data into a deeper, shareable report, all without writing a single formula from scratch. You practiced finding trends, analyzing text-based feedback, generating and refining charts, building formulas with natural language, and producing an audience-ready summary of your findings.
