# Stats for life time listening history in spotify

## How to use:

1. First go to you spotify, select account and then select privacy settings.

2. You should arrive at link like this "https://www.spotify.com/us/account/privacy/".

3. Scroll down and you'll have option to request:

   - Account Data

   - Extended streaming history

   - Technical log information

4. If you want your lifetime streaming history then select "Extended streaming history" box and click on request data.

5. If you just want streaming history from last year then select "Account" box and click on request data. Only track and artist information is available for last year so album tab will remain empty

6. You can also request both at same time too.

7. After you recieve file(s) upload all at once on "https://deepdev79.github.io/spotify/"

8. If you want to see extended history then the files you need to upload might be formated as :

   "Streaming*History_Audio*[time period]\_[file number]"

9. If you only want to see last year streaming history then the files you need to might be formated as:

   "StreamingHistory[file number]"

10. After uploading data you can also filter the data to see your history within certain timeframes.

11. The "other" tab is experimental and doesn't provide much information hence it's not fully maintained

## Note:

- The more accurate term for "Times Played" is "Times visited" i.e. The number of times you visited the track/album/artist be it only for 3-5 seconds, as of now I've intentionally left it as it is.

- Different albums having exact same name in extended history might give out inconsistent results same applies to track names in last year history.

- This is completely frontend pet project using vanilla Javascript. It might take some time to complete the process once you upload the files please be patient.
