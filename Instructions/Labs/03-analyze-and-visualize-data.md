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

In this exercise, you use Microsoft Copilot to analyze a quarterly sales dataset. You use Copilot in Excel to find trends, categorize customer feedback, and generate a chart, then use the Analyst agent to produce a deeper, shareable report from the same data.

This exercise should take approximately **20** minutes to complete.

## Before you start

You need:

- A Microsoft 365 account with a Microsoft 365 Copilot license.
- Access to Excel on the web at [https://www.office.com](https://www.office.com){:target="_blank"} (`https://www.office.com`) or through the desktop app.
- Access to Microsoft Copilot at [https://copilot.cloud.microsoft](https://copilot.cloud.microsoft){:target="_blank"} (`https://copilot.cloud.microsoft`).
- The sample dataset for this exercise. Download [quarterly-sales-data.csv](https://raw.githubusercontent.com/MicrosoftLearning/AB-730-AI-business-professional/main/Allfiles/quarterly-sales-data.csv){:target="_blank"} from `https://raw.githubusercontent.com/MicrosoftLearning/AB-730-AI-business-professional/main/Allfiles/quarterly-sales-data.csv`.

1. Open Excel and create a new blank workbook.
1. Import the data by opening the **Data** tab and selecting **From Text/CSV**, then select the `quarterly-sales-data.csv` file you downloaded.
1. In the preview dialog that appears, leave the **File Origin**, **Delimiter**, and **Data Type Detection** settings at their defaults, then select **Load** to import the data as a table into a new worksheet.
1. Save the workbook to OneDrive as `Quarterly Sales Analysis`.
1. Select the Copilot icon to open the Copilot pane, then select **Edit with Copilot** near the bottom of the pane to turn on Edit with Copilot mode.

> [!IMPORTANT]
> Copilot in Excel can only work with files saved on OneDrive, and your data must be formatted as a table or a supported range. Keep **Edit with Copilot** turned on for the rest of this exercise—with it active, Copilot applies changes, such as new sheets and charts, directly to your workbook instead of asking you to add them.

## Find trends with Copilot in Excel

Your manager asked you to identify how sales are trending across regions and products before a leadership review.

1. In the Copilot pane, enter the following prompt:

    `Summarize total revenue by region and highlight the top-performing region.`

1. Review the summary Copilot generates. Copilot adds the summary to a new sheet automatically since Edit with Copilot is active.
1. Ask a follow-up question to dig deeper:

    `Compare units sold between Q1 and Q2 for each product.`

1. Review the comparison Copilot generates. Copilot adds the product comparison to a new sheet automatically.

## Analyze customer feedback

The dataset includes a column of written customer feedback. Instead of reading each comment individually, you'll ask Copilot to identify recurring themes.

1. In the Copilot pane, enter the following prompt:

    `Review the CustomerFeedback column and identify the major themes.`

1. Review the themes Copilot identifies, such as comments about sizing, durability, or shipping.
1. Ask Copilot to label the sentiment of each comment:

    `Analyze the CustomerFeedback column and label each row by sentiment.`

1. Review the new labeled column Copilot inserts.

> [!TIP]
> If the themes feel too broad, refine your prompt to focus on a specific product or region, such as "Identify themes in feedback for the SummitPeak Backpack only."

## Generate a chart

Leadership wants a visual that's easy to scan during the review meeting.

1. In the Copilot pane, enter the following prompt:

    `Create a bar chart showing total revenue by region.`

1. Review the chart Copilot generates.
1. Refine the chart with a follow-up prompt:

    `Add data labels and sort the regions from highest to lowest revenue.`

1. Review the chart. Copilot adds it to your workbook automatically since Edit with Copilot is active.

## Build a formula with Copilot

You want to calculate the average revenue per unit sold for each row, without writing the formula yourself.

1. Select an empty column next to your data and select the first empty cell in that column.
1. In the Copilot pane, enter the following prompt:

    `Calculate the average revenue per unit sold for each row using the Revenue and UnitsSold columns.`

1. Review the column. Copilot adds the formula for every row automatically since Edit with Copilot is active.

## Generate a deeper report with the Analyst agent

Your manager also wants a polished report that goes beyond a quick summary, including trends and recommendations you can share with the wider team.

1. Open Microsoft Copilot at [https://copilot.cloud.microsoft](https://copilot.cloud.microsoft){:target="_blank"} (`https://copilot.cloud.microsoft`).
1. Select **Analyst** from the agent list.
1. Select the **+** icon and attach your `Quarterly Sales Analysis` Excel workbook from OneDrive.
1. Enter the following prompt:

    `Highlight key trends in revenue and units sold by region and product between Q1 and Q2. Identify any regions or products with declining revenue or units sold, or negative customer feedback themes. Include supporting charts or tables.`

1. Review the report the Analyst agent generates, including any charts or tables.
1. Ask a follow-up question to refine the analysis:

    `Which product had the most negative customer feedback themes, and how does that align with its sales trend?`

1. Ask the agent to prepare the output for your audience:

    `Summarize these findings into three bullet points for a leadership slide.`

You've used Copilot in Excel to explore and visualize a dataset, and the Analyst agent to turn that same data into a deeper, shareable report, all without writing a single formula from scratch.
