## <p align="center"><ins>NSX-T Manager</ins></p>
| > | NSX-T Manager |
| :--- | :---: |
| Command | Description |
| NSX-T Cluster Manager details | ***get managers*** |
| NSX-T Cluster Status | ***get cluster status*** |
| ^ | ***get cluster status verbose*** |
| NSX-T Cluster Configuration Details | ***get cluster config*** |


| header1 | header2 | header3 | header4 |
| --- | --- | --- | --- |
| a | b | c |
| {colspan=4} | < | < | < |
| | {colspan=3} merge 3 cells | < | < |
| d | e | {colspan=2} f | < |


Handlebars.registerHelper('custom_transform', function (options) {
  // get the original output html
  var origin = options.fn(this);
  
  // do some hacks
  var transformed = origin.replaceAll("<td>&lt;</td>", "");
  transformed = transformed.replaceAll(/\<td\>{colspan=([0-9]+)}/g, "<td colspan=\"$1\">");
  
  return new Handlebars.SafeString(transformed);
});