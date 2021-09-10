# Scheduling reports

Open up the schedule page and click **Create schedule**.

![](../../.gitbook/assets/image%20%2837%29.png)

At a minimum you must choose:

* The report which should be generated whenever the schedule runs **\(1\)**
* When the schedule should run \(e.g. Every Monday/Thursday at 8 AM\) **\(2\)**
* The email recipients, or the Google Drive where the report will be exported **\(3\)**

![Schedule options](../../.gitbook/assets/image%20%286%29.png)

Different options will appear depending on whether you choose Email or Google Drive.

#### Email schedule

Choose the file format, either CSV, Excel, PDF or HTML.

{% hint style="info" %}
Contact us at [hello@betterreports.com](mailto:hello@betterreports.com) if you need to customize the email body, subject, sender name, sender email or the name of the attached report file.
{% endhint %}

#### Google Drive schedule

When choosing Google Drive, the report is exported as a Google Sheet every time the schedule runs.  
Several behaviors are offered:

![](../../.gitbook/assets/image%20%2847%29.png)

#### **Schedule Limitations**

Better Reports places some limitations on scheduled runs:

* If a schedule is run manually \(run button\) then the report will cut off at 1 million rows
* If a schedule runs once a day or less then the report will cut off at 100,000 rows
* If a schedule runs more than once a day then the report will cut off at 10,000 rows

There are also hard limitations specific to Excel and Google Sheets:

* Excel files have a limit of 1 million rows
* Google Sheets have a limit of 5 million cells

Should you need reports to run with more rows, we recommend reducing the frequency of your scheduled runs or adding filters to your report. If these limitations don't work for your needs, please reach out to us at [hello@betterreports.com](mailto:hello@betterreports.com) to discuss other options!

