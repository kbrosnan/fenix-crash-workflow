Workflow for crashes in Fenix
* Notice a new crash from data such as Sentry, crash-stats or end user report
** verify that it is a new crash search signature on: 
*** GitHub
*** Sentry 
*** crash-stats 
*** Bugzilla
*** If you don't find anything in Sentry or Crash-stats for the signature ask in #fenix about checking Google Play for crashes that are not caught by the Mozilla crash reporter.
* If you do not find an issue on GitHub or Bugzilla open an issue on GitHub
** label as crash
** Paste stack trace into the issue
** Look at the stack to see if there is any Feature: labels that apply
** List any investigation you have done on the crash
** Add sentry ID for the issue
** Add Crash stats search for the issue
* open an issue on Bugzilla
** link issue to GitHub and Sentry in Bugzilla's see also field 
** make sure signature section is filled out for auto tracking in crash-stats


BZ-# linking in GitHub mozilla-mobile projects

Crash: unexpected exit of the application, not a hang
Signature: First line of the stack trace from the crash

Add crash-stats and sentry to Mike's GitHub tweaks addon

