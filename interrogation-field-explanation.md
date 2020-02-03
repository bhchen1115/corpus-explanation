# Interrogation Corpus: Field Explanation

|Field|Explanation|Values|
|-|-|-|
|case-id|case id| |
|gender|gender|0: male<br>1: female|
|educated-level|education level|0: elementary school or below<br>1: junior high school<br>2: senior high school<br>3: university<br>4: graduated school|
|age|age|0: 14-18<br>1: 18-30<br>2: 30-40<br>3: 40-50<br>4: 50-60<br>5: 60 or above|
|marriage|marriage|0: unmarried<br>1: married<br>2: divorce|
|experience|Number of times participates polygraph test (exclude this time)|0: 0<br>1: 1<br>2: 2<br>3: 3 or more than 3|
|case-type|Type of the case|0: violence<br>1: non-violence|
|violence-type|If it's violence type, which violence type is it is? (multiple choice)|0: intentional murder<br>1: robber<br>2: snatch<br>3: kidnapping<br>4: forcible sexual intercourse<br>5: serious intimidation and extortion<br>6: severe injury|
|non-violence-type|If it's non-violence type, what non-violence type is it? (blank filling)| |
|identity|What identity the subject is? (multiple choice)|0: suspend<br>1: victim<br>2: witness<br>3: other|
|other_identity|If its identity is "other", what identity he/she is? (blank filling)| |
|pretalk-time|How long did they talk before taking the test?|0: within 1 hour<br>1: 1-2 hour<br>2: above 2 hours
|interrogator|Who is the interrogator? (multiple choice)<br>The number indicates different interrogator.| |
|sleep-time|How the time of the subject sleep varies in the past 24 hours? (self-reveal)|0: great<br>1: normal<br>2: worse|
|criminal-record|Did the subject have criminal record? (self-reveal)|0: yes<br>1: no|
|alchol-record|Did the subject drink alcohol in last 24 hours? (self-reveal)|0: yes<br>1: no
|meal-record|Did the subject eat in normal eating time before taking the test? (self-reveal)|0: yes<br>1: no
|medicine-record|Did the subject regularly take medicine?|0: yes<br>1: no
|react-more|In this file, does the polygraph show stronger physical reaction of the subject while he/she is asked to a related question than a control question?|0: yes<br>1: no<br>2: no significant difference|
|final-judge|This case is judged as lie or not?|0: lie<br>1: honest|
|convs|See the following section| |

## convs

|Field|Description|
|-|-|
|q_type|This question is a related question or a control question|
|q_or_a|It's a question or an answer|
|text|Content|
|h|The hour of "the end of the question" or "the start of the answer"|
|m|The minuted of "the end of the question" or "the start of the answer"|
|s|The second of "the end of the question" or "the start of the answer"|
