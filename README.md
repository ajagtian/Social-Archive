Social-Archive
==============

Adaptive Suggestion engine for social communities like Facebook and LinkedIn.



Social Networks like Facebook have a notion of events, which are attended by a lot many people.
However there has't ever been an Event Suggestion Engine provided by Facebook yet, and thus users have to search for 
keywords on Facebook time and time again to look for events they like to attend. Strangely though the choices and the search query of the events for a user may remain same for over a short period of time. So, person may miss an important event beacuse - he was not invited to it or he did not put the effort to search for it.

<b>Social-Archive</b> is an adaptive suggestion engine(presently) for Facebook Events/Groups/Pages.  Simple requirements of this application are - 
(1) A user logs in through Facebook, (2) sets his preferred event types, and (3)preferred locations of the events, and that's it.

The application mines Facebook's Open Graph Api and brings a list of all the user's favorite events, ranked accoring to a likebility factor. So now a user may not have to search Facebook every couple of days for new events, instead all the events in the categories he wishes to attend will be listed to him. And then a user could RSVP event, add a evnt reminder to his calendar, etc.

Check out the application at - 

<blockquote><a hraf = "http://social-archive.elasticbeanstalk.com">http://social-archive.elasticbeanstalk.com</a></blockquote>


Apart from the favorites users also get to see a list of trending events in their ecosystem of Facebook, again ranked as per users likebility.

<blockquote>Social-Archive also provides developers with a social API which they can consume in their application for similar purposes, need not redo the work of this one.</blockquote>

Version 2 of this application will have integration for LinkedIn Events.