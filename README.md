I'm not sure why GitHub profiles have READMEs, but if you ever visit mine, be sure to do the following to ensure you are viewing my profile correctly:

    Open inspect element
    Find the following nested element
```
<table class="ContributionCalendar-grid js-calendar-graph-table" .... >
  <caption .... ></caption>
  <thread>[...]</thread>
  <tbody>
    <tr style="height: 10px">
	<td class="ContributionCalendar-label" .... >[...]</td>
	<td id="contribution-day-component-1-0" .... ></td> <!-- <- This one right here! -->
```
    In the style editor, there should be a property called background-color. Set it to the color #39d353

    Next, find the h2 with the class "f4 text-normal mb-2"
    It should have the text: "{n} contributions made in the last year"
    Kindly, change the text to say something similar to "1343758947861432 contributions made in the last year"

Many thanks in advance. I hope you have a pleasant day :)
