# pictureFrame
Picture Frame v1.5+ Language 

Possible options for new language are the following:
<li>[af] Afrikaans</li>
<li>[al] Albanian</li>
<li>[ar] Arabic</li>
<li>[az] Azerbaijani</li>
<li>[bg] Bulgarian</li>
<li>[ca] Catalan</li>
<li>[cz] Czech</li>
<li>[da] Danish</li>
<li>[de] German</li>
<li>[el] Greek</li>
<li>[en] English</li>
<li>[eu] Basque</li>
<li>[fa] Persian (Farsi)</li>
<li>[fi] Finnish</li>
<li>[fr] French</li>
<li>[gl] Galician</li>
<li>[he] Hebrew</li>
<li>[hi] Hindi</li>
<li>[hr] Croatian</li>
<li>[hu] Hungarian</li>
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
<li>[es] Spanish</li>
<li>[sr] Serbian</li>
<li>[th] Thai</li>
<li>[tr] Turkish</li>
<li>[ua] Ukrainian</li>
<li>[vi] Vietnamese</li>
<li>[zh_cn] Chinese Simplified</li>
<li>[zh_tw] Chinese Traditional</li>
<li>[zu] Zulu</li>

#END
<hr />
<h3>Step 1</h3>
Please change the version tag to the actual date when you're editing the file, that's how the app would know if there is a newer language file is.

<pre><code>"version": "20230521"</code></pre>

The format for the date is YYYYMMDD like 2023 05 21 (without spaces)

<h3>Step 2</h3>
Add the new language name and code into the availableLanguages array. (Please use the name as they would use in that language)
<pre>"availableLanguages": {
  "English": "en",
  "Français": "fr",
  "Deutsch": "de",
  "Español": "es"$${\color{red},$\color[RGB]{155,127,0} hello$
  "Magyar": "hu"}$$
}
 </pre>
 <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 55 20" fill="none">
    <text x="0" y="15" fill="#4285f4">T</text>
    <text x="12" y="15" fill="#ea4335">E</text>
    <text x="21" y="15" fill="#fbbc05">S</text>
    <text x="30" y="15" fill="#4285f4">T</text>
    <text x="40" y="15" fill="#389738">!</text>
    <text x="45" y="15" fill="#ea4335">:</text>
</svg>
 <h3>Step 3</h3>
 Edit the following block change the language code at the front and the name inside to the actual code and name, then you can translate the right side of the block..
 
 <pre><code>"en": {
  "Name": "English",
  "Author": "AmL",
  "dv": "___________",
  "Monday": "Monday",
  "Tuesday": "Tuesday",
  "Wednesday": "Wednesday",
  "Thursday": "Thursday",
  "Friday": "Friday",
  "Saturday": "Saturday",
  "Sunday": "Sunday",
  "Mon": "Mon",
  "Tue": "Tue",
  "Wed": "Wed",
  "Thu": "Thu",
  "Fri": "Fri",
  "Sat": "Sat",
  "Sun": "Sun",
  "am": "am",
  "pm": "pm",
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
  "Feels_like": "Feels like",
  "Sunrise": "Sunrise",
  "Sunset": "Sunset",
  "at_noon": "at noon",
  "cloudiness": "cloudiness",
  "wind": "wind",
  "daily_high": "daily high",
  "daily_low": "daily low",
  "chance_of_precipitation": "chance of precipitation"
  } 
 </code></pre>
