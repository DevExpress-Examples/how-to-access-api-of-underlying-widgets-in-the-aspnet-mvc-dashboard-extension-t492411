<!-- default file list -->
*Files to look at*:

* [HomeController.cs](./CS/MVCxDashboard_UnderlyingWidgets/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/MVCxDashboard_UnderlyingWidgets/Controllers/HomeController.vb))
* [Global.asax.cs](./CS/MVCxDashboard_UnderlyingWidgets/Global.asax.cs) (VB: [Global.asax.vb](./VB/MVCxDashboard_UnderlyingWidgets/Global.asax.vb))
* [WidgetsCustomization.js](./CS/MVCxDashboard_UnderlyingWidgets/Scripts/WidgetsCustomization.js) (VB: [WidgetsCustomization.js](./VB/MVCxDashboard_UnderlyingWidgets/Scripts/WidgetsCustomization.js))
* [Index.cshtml](./CS/MVCxDashboard_UnderlyingWidgets/Views/Home/Index.cshtml)
* [_Layout.cshtml](./CS/MVCxDashboard_UnderlyingWidgets/Views/Shared/_Layout.cshtml)
<!-- default file list end -->
# How to access API of underlying widgets in the ASP.NET MVC Dashboard Extension
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/t492411/)**
<!-- run online end -->


This example demonstrates how to customize client widgets used to visualize data within dashboard items at runtime using <a href="https://documentation.devexpress.com/#Dashboard/clsDevExpressDashboardWebScriptsASPxClientDashboardtopic">ASPxClientDashboard</a>'s API. This approach is described in greater detail in the <a href="https://documentation.devexpress.com/#Dashboard/CustomDocument117573">Access to Underlying Widgets</a> help topic. <br>The following options are changed

* Highlighting of the hovered grid row is enabled in the underlying <a href="https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDataGrid/">dxDataGrid</a> in the <a href="https://documentation.devexpress.com/#Dashboard/DevExpressDashboardWebScriptsASPxClientDashboard_ItemWidgetCreatedtopic">ItemWidgetCreated</a> event handler.
* A standard tooltip that is invoked when an end-user hovers over a chart series point is disabled. You can invoke a tooltip by clicking the required label on the argument axis. The argumentAxisClick event is used for this purpose. Subscription and unsubscription to/from the argumentAxisClick event are performed in the <a href="https://documentation.devexpress.com/#Dashboard/DevExpressDashboardWebScriptsASPxClientDashboardViewer_ItemWidgetUpdatedtopic">ItemWidgetUpdated</a> and <a href="https://documentation.devexpress.com/#Dashboard/DevExpressDashboardWebScriptsASPxClientDashboardViewer_ItemWidgetUpdatingtopic">ItemWidgetUpdating</a> event handlers respectively.
* A pie legend is shown for the underlying <a href="https://js.devexpress.com/Documentation/ApiReference/Data_Visualization_Widgets/dxPieChart/">dxPieChart</a>.

<br/>


