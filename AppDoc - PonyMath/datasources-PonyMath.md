# Power App Documentation \- PonyMath

| Property                   | Value                                                          |
| -------------------------- | -------------------------------------------------------------- |
| App Name                   | PonyMath                                                       |
| App Logo                   | <img alt="App Logo" src="resources/applogo.png" width="200" /> |
| Documentation generated at | Monday, 21 November 2022 1:25 pm                               |

- [Overview](index-PonyMath.md)
- [App Details](appdetails-PonyMath.md)
- [Variables](variables-PonyMath.md)
- [DataSources](datasources-PonyMath.md)
- [Resources](resources-PonyMath.md)
- [Controls](controls-PonyMath.md)

## DataSources

A total of 4 DataSources are located in the app:

### CustomGallerySample

| Property | Value                |
| -------- | -------------------- |
| Name     | CustomGallerySample  |
| Type     | StaticDataSourceInfo |

#### DataSource Properties

| Property           | Value                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Data               | \[{"SampleHeading":"Lorem ipsum 1","SampleImage":"\/ctrllib\/image\/images\/SampleImage.svg","SampleText":"Lorem ipsum dolor sit amet, consectetur adipiscing elit."},{"SampleHeading":"Lorem ipsum 2","SampleImage":"\/ctrllib\/image\/images\/SampleImage.svg","SampleText":"Suspendisse enim metus, tincidunt quis lobortis a, fringilla dignissim neque."},{"SampleHeading":"Lorem ipsum 3","SampleImage":"\/ctrllib\/image\/images\/SampleImage.svg","SampleText":"Ut pharetra a dolor ac vehicula."},{"SampleHeading":"Lorem ipsum 4","SampleImage":"\/ctrllib\/image\/images\/SampleImage.svg","SampleText":"Vestibulum dui felis, fringilla nec mi sed, tristique dictum nisi."}\] |
| IsSampleData       | True                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| IsWritable         | False                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| OrderedColumnNames | <table><tr><td>OrderedColumnNames</td><td><table><tr><td>SampleImage</td></tr><tr><td>SampleHeading</td></tr><tr><td>SampleText</td></tr></table></td></tr></table>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| OriginalName       | CustomGallerySample                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| OriginalSchema     | \*\[SampleHeading:s, SampleImage:i, SampleText:s\]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Schema             | \*\[SampleHeading:s, SampleImage:i, SampleText:s\]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |

### ListboxSample

| Property | Value                |
| -------- | -------------------- |
| Name     | ListboxSample        |
| Type     | StaticDataSourceInfo |

#### DataSource Properties

| Property           | Value                                         |
| ------------------ | --------------------------------------------- |
| Data               | \[{"Value":"1"},{"Value":"2"},{"Value":"3"}\] |
| IsSampleData       | True                                          |
| IsWritable         | False                                         |
| OrderedColumnNames | Value                                         |
| OriginalName       | ListboxSample                                 |
| OriginalSchema     | \*\[Value:s\]                                 |
| Schema             | \*\[Value:s\]                                 |

### MaxTimesTableNumbers

| Property | Value                    |
| -------- | ------------------------ |
| Name     | MaxTimesTableNumbers     |
| Type     | CollectionDataSourceInfo |

#### DataSource Properties

| Property          | Value |
| ----------------- | ----- |
| IsComponentScoped | False |
| IsSampleData      | False |
| IsWritable        | True  |

### PaymentCoins

| Property | Value                    |
| -------- | ------------------------ |
| Name     | PaymentCoins             |
| Type     | CollectionDataSourceInfo |

#### DataSource Properties

| Property          | Value |
| ----------------- | ----- |
| IsComponentScoped | False |
| IsSampleData      | False |
| IsWritable        | True  |
