# cs224u-project

the merged and processed data 'TED.csv' including columns:
* 'comments': Number of first level comments for a TED talk
* 'description': Short text of the talk's content
* 'duration': Number of seconds for the duraction of the talk
* 'event': Which event this belongs to
* 'film_date': Unix Timstamp of the filming
* 'languages': Number of language the talk is available in
* 'main_speaker': Name of the main speaker
* 'name': Name of the TED talk
* 'num_speaker': Number of speakers in the talk, ranges from 1-5
* 'published_date': Unix timestamp for publications on TED.com
* 'ratings': Stringified dictionary mapping reactions to counts (processed this and appended to the end, 14 reactions with their counts)
* 'related_talks': 
* 'speaker_occupation': 
* 'tags': 
* 'title': 
* 'url': string, merging the files based on this column
* 'views': Number of viewings on TED.com
* 'transcript': long text for the entire talk
* The following 14 columns are reaction counts from 'ratings':
  'Confusing', 'Persuasive', 'Jaw-dropping',
  'Informative', 'Beautiful', 'Inspiring', 'Courageous', 'OK', 'Funny',
  'Unconvincing', 'Ingenious', 'Fascinating', 'Longwinded', 'Obnoxious'
