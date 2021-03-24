# Congressman-and-Congresswoman-Twitter-Text-mining-Project

Descriptions


Twitter allows elected public officials to communicate with millions of other people
over the internet. With each tweet, 280 characters are given to compose a message
that will ultimately influence the public’s perception of that individual. Since 535/535
members of Congress have twitter handles and consistently tweet, this public
information can be analyzed to gain insights on where a politician stands on a policy
issue.
For this project, we will be analyzing the tweets of all members of Congress during
the height of the Black Lives Matter and George Floyd protests between May 26th
and June 30th. We aim to determine if there was a difference in the language used
by members of Congress from different parties throughout the protests.


Source Data


For this project, we are going to leverage Alex Litel’s Github Repository
‘congresstweets’, which automatically downloads the tweets of members of
Congress, as our main data source. This data is collected nightly, but we will be
using the data from May 26th through June 30th, as this was the height of the Black
Live Matter and George Floyd protests.
The data is provided as JSON files, which we will process using Python on Google
Colab, accessed from a shared Google Drive folder. The JSON files between our
chosen dates are 55.6MB. The data is licensed under MIT’s Open Source Licensing,
found at the link below.


Source links:


https://github.com/alexlitel/congresstweets
https://opensource.org/licenses/mit-license.php


Questions to be Answered


- Are there any members of Congress whose tweets differ from those of others
in their parties.
- What do tweets tell us about the messaging of a political party?
- Do attributes like subjectivity and polarity significantly differ between
Republicans and Democrats?
- How does this change over time?
- What other context can this text analytics method be applied to?
- Can we detect similar trends of tweet behavior during the election?
What about during impeachment?
