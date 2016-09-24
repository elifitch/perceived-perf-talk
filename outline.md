* Title
* Introduction - me; Who me is, what I do, my site
* When we're talking about web performance what we're really talking about is time
* But time is a funny thing, 1 minute of objective time can feel like a very different amount of subjective time (perc time) depending on situation
* We optimize for objective time; we optimize for seconds, kilobytes, and requests; and hope that this makes people satisified, without necessarily directly thinking of people
* [Chart of 100ms, 1000ms, 10000ms impact on attention] We hope that by optimizing for objective time, we're having an impact on percieved time. We optimize for 
* Sometimes we work in environments where we can't control everything, we can't make our app substantially faster. Or we have to match a competitors speed but we're limited in how close we can get.
* By better understanding how humans percieve time, we can help our apps feel faster withough making them physically faster.
* Rule 1: explained waits feel shorter than unexplained waits. Give people an idea as to what the app is doing, otherwise it'll feel broken.
* Rule 2: certain waits feel shorter than uncertain waits. Progress bars, estimations of time.
* Researchers at Carnegie Mellon showed that animated progress bars are better (http://www.chrisharrison.net/projects/progressbars2/ProgressBarsHarrison.pdf)
* Rule 3: active waits feel shorter than passive waits. Airline story from smashing mag. Great example is slack, using a complex animation and quotes to read as the app boots.
* Active vs Passive goes further. "Active" just means that the user is engaged while waiting. We can use this to our advantage by employing predictive design.
* What if, based on current user actions, we could predict their next action, and preload it so it is ready the moment the user That would turn the entire wait into an "active" wait. But instead of active in that they're watching an animation, or reading a quote, its active in that the user is engaged in whatever they were doing.
* Essentially this would mean no perceived wait at all.
* 
* 
* 
* 

Notes:
* An idle tab is a terrible thing to waste. Always be thinking about what can be loaded in the background.