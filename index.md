## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ridg100/ridg100.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files. Test this


<script src="https://scheduler-amgenpatientservices.cs36.force.com/RepathaFRSScheduler/lightning/lightning.out.js">
</script>

<script>
$Lightning.use("runtime_appointmentbooking:lightningOutGuest",
function() { // Callback once framework and app load
$Lightning.createComponent(
"lightning:flow", // top-level component of your app
{ }, // attributes to set on the component when created
"lexcontainer", // the DOM location to insert the component
function(component) { // API name of the Flow
component.startFlow(”Repatha_Scheduler_Inbound_Guest_New_Appointment”);
}
);
}, 'https://scheduler-amgenpatientservices.cs36.force.com/RepathaFRSScheduler/' // Site endpoint


  

