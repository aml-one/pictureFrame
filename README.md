<h2>Picture Frame v1.5+ Language file</h2>

<u>Possible options for new language are the following:</u>
<li>[af] Afrikaans</li>
<li>[al] Albanian</li>
<li>[ar] Arabic ✓</li>
<li>[az] Azerbaijani</li>
<li>[bg] Bulgarian</li>
<li>[ca] Catalan</li>
<li>[cz] Czech</li>
<li>[da] Danish</li>
<li>[de] German ✓</li>
<li>[el] Greek</li>
<li>[en] English ✓</li>
<li>[eu] Basque</li>
<li>[fa] Persian (Farsi)</li>
<li>[fi] Finnish</li>
<li>[fr] French ✓</li>
<li>[gl] Galician</li>
<li>[he] Hebrew</li>
<li>[hi] Hindi</li>
<li>[hr] Croatian</li>
<li>[hu] Hungarian ✓</li>
<li>[id] Indonesian</li>
<li>[it] Italian</li>
<li>[ja] Japanese</li>
<li>[kr] Korean</li>
<li>[la] Latvian</li>
<li>[lt] Lithuanian</li>
<li>[mk] Macedonian</li>
<li>[no] Norwegian</li>
<li>[nl] Dutch</li>
<li>[pl] Polish</li>
<li>[pt] Portuguese</li>
<li>[pt_br] Português Brasil</li>
<li>[ro] Romanian</li>
<li>[ru] Russian</li>
<li>[se] Swedish</li>
<li>[sk] Slovak</li>
<li>[sl] Slovenian</li>
<li>[es] Spanish ✓</li>
<li>[sr] Serbian</li>
<li>[th] Thai</li>
<li>[tr] Turkish</li>
<li>[ua] Ukrainian</li>
<li>[vi] Vietnamese</li>
<li>[zh_cn] Chinese Simplified</li>
<li>[zh_tw] Chinese Traditional</li>
<li>[zu] Zulu</li>

<hr />

<h4>File format is <b>JSON</b>, please use comma where it needed. You can see the structure of the file</h4>
<h5>The file need to be edited here in this github page, the app is downloading the new file from here</h5>
<br />
<br />
<h3>Step 1</h3>
Please change the version tag to the actual date when you're editing the file, that's how the app would know if there is a newer language file is.

<pre><code>"version": "20230521"</code></pre>

The format for the date is YYYYMMDD like 2023 05 21 (without spaces)

<hr />
<h3>Step 2</h3>
Add the new language name and code into the <b>availableLanguages</b> array. (<i>Please use the name as they would use in that language</i>)
<br />
Eg: <code>"Magyar": "hu"</code> for Hungarian<br /><br />

<pre><code>"availableLanguages": {
  "English": "en",
  "Français": "fr",
  "Deutsch": "de",
  "Español": "es",
  "Magyar": "hu"
}</code></pre>

<hr />

 <h3>Step 3</h3>
 Edit the following block change the language code "<b>en</b>" at the front and the "<b>Name</b>" inside to the actual name, then you can translate the right side of the block..<br />
 Also you can add your name to the <b>"Author"</b> tag..
 <br /><br />
 
 <pre><code>"en": {
  "Name": "English",
  "Author": "AmL",
  "Comment1": "______Day_names______",
  "Monday": "Monday",
  "Tuesday": "Tuesday",
  "Wednesday": "Wednesday",
  "Thursday": "Thursday",
  "Friday": "Friday",
  "Saturday": "Saturday",
  "Sunday": "Sunday",
  "Tomorrow": "Tomorrow",
  "Comment2": "______Day_names_in_short______",
  "Mon": "Mon",
  "Tue": "Tue",
  "Wed": "Wed",
  "Thu": "Thu",
  "Fri": "Fri",
  "Sat": "Sat",
  "Sun": "Sun",
  "Comment3": "______AM/PM_indicators______",
  "am": "am",
  "pm": "pm",
  "Comment4": "______Month_names_in_short______",
  "Jan": "Jan",
  "Feb": "Feb",
  "Mar": "Mar",
  "Apr": "Apr",
  "May": "May",
  "Jun": "Jun",
  "Jul": "Jul",
  "Aug": "Aug",
  "Sep": "Sep",
  "Oct": "Oct",
  "Nov": "Nov",
  "Dec": "Dec",
  "Comment5": "______Weather_related_expressions______",
  "Feels_like": "Feels like",
  "Sunrise": "Sunrise",
  "Sunset": "Sunset",
  "at_noon": "at noon",
  "cloudiness": "cloudiness",
  "wind": "wind",
  "daily_high": "daily high",
  "daily_low": "daily low",
  "chance_of_precipitation": "chance of precipitation",			
  "Comment6": "______Wind_directions_in_initials______",
  "N": "N",
  "NNE": "NNE",
  "NE": "NE",
  "ENE": "ENE",
  "E": "E",
  "ESE": "ESE",
  "SE": "SE",
  "SSE": "SSE",
  "S": "S",
  "SSW": "SSW",
  "SW": "SW",
  "WSW": "WSW",
  "W": "W",
  "WNW": "WNW",
  "NW": "NW",
  "NNW": "NNW"
}
 </code></pre>
 
 <hr />
 <h4>Wind direction shorts:</h4>
 <p>Please try to keep them short</p>
 <br />
<table>
<tr>
  <td>"N"   </td><td> North</td>
  </tr>
<tr>
  <td>"NNE" </td><td> North North East</td>
</tr>
<tr>
  <td>"NE"  </td><td> North East</td>
</tr>
<tr>
  <td>"ENE"  </td><td> East North East</td>
</tr>
<tr>
  <td>"E"   </td><td> East</td>
</tr>
<tr>
  <td>"ESE" </td><td> East South East</td>
</tr>
<tr>
  <td>"SE"  </td><td> South East</td>
</tr>
<tr>
  <td>"SSE" </td><td> South South East</td>
</tr>
<tr>
  <td>"S"   </td><td> South</td>
</tr>
<tr>
  <td>"SSW" </td><td> South South West</td>
</tr>
<tr>
  <td>"SW"  </td><td> South West</td>
</tr>
<tr>
  <td>"WSW" </td><td> West South West</td>
</tr>
<tr>
  <td>"W"   </td><td> West</td>
</tr>
<tr>
  <td>"WNW" </td><td> West North West</td>
</tr>
<tr>
  <td>"NW"  </td><td> North West</td>
</tr>
<tr>
  <td>"NNW" </td><td> North North West</td>
</tr>
</table>
