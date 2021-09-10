# Text fields

You can filter text fields with one of these operators:

* Is / Is not
* Contains / Doesn't contain
* Starts with / Doesn't start with
* Ends with / Doesn't end with
* Like / Not like

Simply choose an operator \(1\) and choose **one or more** values.

![](../../.gitbook/assets/image%20%2826%29.png)

#### Is / Is not

If you choose **is** or **is not** you can input multiple values. Rows will show if they match **ANY of the values**.  
In our example above, rows will match if the product type is either 'Baby' or 'Garden'.  
Similarly, you can use **is not** to find rows that don't match **ANY of the values** \(in other words, rows that match NONE of the values\).

**Is** and **Is not** also allow the use of special built-in operands: **\[Unknown\]** and **&lt;empty&gt;**.

![](../../.gitbook/assets/image%20%2866%29.png)

Use **\[Unknown\]** to match all rows that don't have a value \(the value is NULL\).

Use **&lt;empty&gt;** to match all rows that have a blank value \(empty string\).

{% hint style="warning" %}
Don't type in '\[Unknown\]' or '&lt;empty&gt;' with the keyboard. Instead, always select it from the drop-down list.
{% endhint %}

#### Like / Not like

Like and not like are powerful operators that use special wildcard characters to match certain patterns.

| Wildcard character | Description | Example |
| :--- | :--- | :--- |
| **%** | Any string of zero or more characters | **%computer%** finds rows with the word 'computer' |
| **\_** _\(underscore\)_ | Any single character | **\_ean** finds rows with a 4 characters value that ends in 'ean'. \(Dean, Sean, and so on\). |
| **\[ \]** | Any single character within the specified range \(e.g. \[a-f\]\) or set \(e.g. \[abcdef\]\) | **\[C-P\]arsen** finds rows that end with 'arsen' and start with any single character between C and P \(Carsen, Larsen, Karsen, etc\). |
| **\[^\]** | Any single character not within the specified range \(e.g. \[^a-f\]\) or set \(e.g. \[^abcdef\]\) | **\[^abc\]ing** finds rows that end in 'ing' and don't start with 'a' or 'b' or 'c' \('sing', 'king', etc\). |

You can also use multiple wildcards at a time.  
For example, **\[a-f\]\_\[^et\]%ing%** finds rows that start with a character between 'a' and 'f', followed by any character, followed by a character that is neither 'e' or 't', followed by any characters, followed by 'ing', followed by any characters.

