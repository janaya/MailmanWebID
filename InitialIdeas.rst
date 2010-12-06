= Mailman WebID initial ideas:

== Basic features:
=== Web interface
 1. subscription through WebID (disable majordomo-style commands?)
 2. web interface authentication with WebID (view subscribers list, view archive in case of private)
 
 
=== Semantic formats
 3. generate archives with RDFa (using SWAML[4] ontology) + link to pure RDF
 4. generate FOAF group with the subscribers lists
 5. generate FOAF profile with each subscriber (with knows? for the people he/she answered mail and the list of SIOC posts he/she generated)
 
=== mail content
 6. header in mail that include the URI to the archive (Archived-At header: --> see w3c lists). Maybe also in the same mail as text [1]
 7. embed attachments (ie, see pictures in the webpage)

== Future enhancements:

 1. Search -> pluggable archiving module. ACLs.
 2. Dahsboard module
   - Activity 
   - Stats module -- vis:: protovis (django-mailman-graph)
 3. Threaded browsing, (exhibit[3]...)
 4. Trust Chains for Invites + Weighted Admission (lists that can only grow by defined trust chains). -> Rules Plugin.
 5. Possibility of replying to posts from web interface
 6. Multitools integration. F.i,  MediaWiki --> this list has this wiki, this wiki can be edited by people in this list.
 7. replacing e-mail with WebID + Atom/restmail [2]
 8. Spam rules: moderation bits, fixing email spam using WebIDs for DKIM identity etc

== Acknowledgments

Thanks to Henry Story and foaf-protocols people ideas

[1] http://tools.ietf.org/html/rfc5064
[2] http://markmail.org/thread/zi546wy4x6avbbff, http://lists.foaf-project.org/pipermail/foaf-protocols/2010-September/003509.html, http://esw.w3.org/Pingback, http://ods.openlinksw.com/wiki/ODS/OdsMail, http://www.prescod.net/rest/restmail/, http://restmail.org/, https://developer.mozilla.org/en/RDF_in_Fifty_Words_or_Less
[3] http://www.simile-widgets.org/exhibit/
[4] http://swaml.berlios.de/

