---
title: Detailed Schedule
---

<h2><div id = "LOCAL_TIME"></div></h2>

<table>
  <thead>
    <tr>
      <th>Day</th>
      <th>Date</th>
      <th>Topics</th>
      <th>Speakers</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Day 1</td>
      <td>Monday</td>
      <td><b>Introduction to Embedded ML (tinyML)</b><br>
        &nbsp;&nbsp;&nbsp;<i>1:00pm</i>&nbsp; Conference Opening and Schedule<br>
        &nbsp;&nbsp;&nbsp;<i>1:20pm</i>&nbsp; Introduction and Applications of Embedded ML<br>
        &nbsp;&nbsp;&nbsp;<i>2:20pm</i>&nbsp; Break<br>
        &nbsp;&nbsp;&nbsp;<i>2:30pm</i>&nbsp; Introduction to Machine Learning<br>
        &nbsp;&nbsp;&nbsp;<i>3:50pm</i>&nbsp; Day Closing<br>
      </td>
      <td>
        <a href="https://scholar.harvard.edu/vijay-janapa-reddi/home">Vijay Janapa Reddi</a> of Harvard University<br>
        <a href="https://laurencemoroney.com/">Laurence Moroney</a> of Google</td>
    </tr>
    <tr>
      <td>Day 2</td>
      <td>Tuesday</td>
      <td><b>Hands on Embedded ML - Vision and Audio</b><br>
        &nbsp;&nbsp;&nbsp;<i>1:00pm</i>&nbsp; Day Opening<br>
        &nbsp;&nbsp;&nbsp;<i>1:10pm</i>&nbsp; Hands on Embedded ML - Vision and Audio<br>
        &nbsp;&nbsp;&nbsp;<i>3:00pm</i>&nbsp; Break<br>
        &nbsp;&nbsp;&nbsp;<i>3:10pm</i>&nbsp; Multilingual Keyword Spotting<br>
        &nbsp;&nbsp;&nbsp;<i>3:50pm</i>&nbsp; Day Closing
      </td>
      <td>
        <a href="https://brianplancher.com/">Brian Plancher</a> of Harvard University<br>
        <a href="https://markmaz.com/">Mark Mazumder</a> of Harvard University
      </td>
    </tr>
    <tr>
      <td>Day 3</td>
      <td>Wednesday</td>
      <td><b>Sensors and Ethical Issues for ML and IoT</b><br>
        &nbsp;&nbsp;&nbsp;<i>1:00pm</i>&nbsp; Day Opening<br>
        &nbsp;&nbsp;&nbsp;<i>1:10pm</i>&nbsp; Introduction to Sensors for IoT<br>
        &nbsp;&nbsp;&nbsp;<i>1:55pm</i>&nbsp; Break<br>
        &nbsp;&nbsp;&nbsp;<i>2:10pm</i>&nbsp; Ethical Issues in ML and IoT<br>
        &nbsp;&nbsp;&nbsp;<i>3:10pm</i>&nbsp; Breakout Discussions<br>
        &nbsp;&nbsp;&nbsp;<i>3:30pm</i>&nbsp; Full Group Discussions<br>
        &nbsp;&nbsp;&nbsp;<i>3:50pm</i>&nbsp; Day Closing
      </td>
      <td>
        <a href="https://cs.unu.edu/people/experts/15926.html">Serge Stinckwich</a> of UNU<br>
        TBD
      </td>
    </tr>
    <tr>
      <td>Day 4</td>
      <td>Thursday</td>
      <td><b>Hands on Embedded ML - Motion/Anomaly Detection and Scientific Applications</b><br>
        &nbsp;&nbsp;&nbsp;<i>1:00pm</i>&nbsp; Day Opening<br>
        &nbsp;&nbsp;&nbsp;<i>1:10pm</i>&nbsp; Hands on Embedded ML - Motion/Anomaly Detection and Scientific Applications<br>
        &nbsp;&nbsp;&nbsp;<i>3:00pm</i>&nbsp; Break<br>
        &nbsp;&nbsp;&nbsp;<i>3:10pm</i>&nbsp; Applications of TinyML for Atmospheric Monitoring<br>
        &nbsp;&nbsp;&nbsp;<i>3:50pm</i>&nbsp; Day Closing
      </td>
      <td>
        <a href="https://www.linkedin.com/in/marcelo-jose-rovai-brazil-chile/">Marcelo Rovai</a> of UNIFEI<br>
        <a href="http://mpstewart.net/">Matthew Stewart</a> of Harvard University</td>
    </tr>
    <tr>
      <td>Day 5</td>
      <td>Friday</td>
      <td><b>Academic Network Next Steps and Closing Keynotes</b><br>
        &nbsp;&nbsp;&nbsp;<i>1:00pm</i>&nbsp; Day Opening and Academic Network Next Steps<br>
        &nbsp;&nbsp;&nbsp;<i>1:35pm</i>&nbsp; AI and Education<br>
        &nbsp;&nbsp;&nbsp;<i>2:10pm</i>&nbsp; Break<br>
        &nbsp;&nbsp;&nbsp;<i>2:20pm</i>&nbsp; Responsible Embedded AI<br>
        &nbsp;&nbsp;&nbsp;<i>3:05pm</i>&nbsp; TensorFlowLite for Microcontrollers<br>
        &nbsp;&nbsp;&nbsp;<i>3:50pm</i>&nbsp; Workshop Closing
      </td>
      <td>
        <a href="http://users.ictp.it/~mzennaro/">Marco Zenaro</a> of ICTP<br>
        <a href="https://www.linkedin.com/in/halspeed/">Hal Speed</a> of Robotical<br>
        <a href="https://www.susan-kennedy.com/">Susan Kennedy</a> of Santa Clara University<br>
        <a href="https://petewarden.com/">Pete Warden</a> of Google</td>
    </tr>
  </tbody>
</table>

<script>
  var start = new Date('10/18/2021 1:00:00 PM UTC');
  var end = new Date('10/18/2021 4:00:00 PM UTC');
  var localTime = start.toLocaleTimeString([], {timeStyle: 'short'}) + " to " + end.toLocaleTimeString([], {timeStyle: 'short'});
  var startString = "The workshop will run each day from 1:00 PM to 4:00 PM GMT which is "
  var endString = " in your local timezone (according to your computer system time). All times below are in GMT. Exact timing subject to change."
  document.getElementById('LOCAL_TIME').innerHTML = startString + localTime + endString;
</script>