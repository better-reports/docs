# Configuring a report

* Configuring a report is similar for all [visual types](../choosing-a-visual-type.md)
* Each visual type offers different roles
* You configure a report by assigning data fields to the roles available
* Depending on its type and cardinality, a role may be assigned one or several dimensions or measures



#### Table report roles

| Name                     | Type      | Cardinality |
| ------------------------ | --------- | ----------- |
| **Dimensions**           | Dimension | 0 to many   |
| **Measures**             | Measure   | 0 to many   |
| **Row color saturation** | Measure   | 0 or 1      |
| **Hidden field**         | Dimension | 0 to many   |

####

#### Bar / Line report roles

| Name         | Type      | Cardinality |
| ------------ | --------- | ----------- |
| **X axis**   | Dimension | 1           |
| **Y axis 1** | Measure   | 1 or many   |
| **Y axis 2** | Measure   | 0 or many   |
| **Color**    | Dimension | 0 or 1      |

####

#### Matrix report roles

| Name                      | Type      | Cardinality |
| ------------------------- | --------- | ----------- |
| **Columns**               | Dimension | 0 to many   |
| **Rows**                  | Dimension | 0 to many   |
| **Cell text**             | Measure   | 0 or 1      |
| **Cell color saturation** | Measure   | 0 or 1      |

####

#### Scatter plot report roles

| Name                | Type      | Cardinality |
| ------------------- | --------- | ----------- |
| **Horizontal axis** | Measure   | 1           |
| **Vertical axis**   | Measure   | 1           |
| **Bubble color**    | Dimension | 0 or 1      |
| **Bubble size**     | Measure   | 0 or 1      |
| **Split**           | Dimension | 0 to many   |
