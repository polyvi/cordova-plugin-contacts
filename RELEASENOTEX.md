<!--
#
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#  KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.
#
-->
# Release Note X


### 0.2.7 Mon Jan 27 2014 16:41:18 GMT+0800 (CST)
 *  added releasenotex.md
 *  CB-5719 Updated version and RELEASENOTES.md for release 0.2.7
 *  CB-5658 Update license comment formatting of doc/index.md
 *  B-5658 Add doc.index.md for Contacts plugin
 *  CB-5658 Delete stale snapshot of plugin docs
 *  [CB-5565] Incremented plugin version on dev branch.
 *  [CB-5565] Updated version and RELEASENOTES.md for release 0.2.6
 *  Fix bad commit/merge
 *  CB-3035 Fix issue with windows new line char \n\r
 *  wrong example given
 *  docs added
 *  FxOS name fields are arrays hackedSearch refactored search based on find commented out
 *  search hacked via getAll
 *  search added - no idea if this is working
 *  createMozillaFromCordova and vice versa are used to translate contact objects from one API to another.
 *  add/remove working
 *  save is working
 *  attempt to save is failing trying to limit the translated contact fields to name and familyName, but still failing
 *  save is linked with the proxy contact.name doesn't exist www/Contact.js#Contact.prototype.save check on which side is the error
 *  CB-5214 Make mobile spec tests on WP8 to run w/o user interaction + Sync with cordova-mobile-spec
 *  CB-5525 WP8. Contacts Api fails in case of there is special character in contact field
 *  fixed ubuntu policy error
 *  [ubuntu] specify policy_group
 *  add ubuntu platform
 *  CB-3035 Fix issue with windows new line char \n\r
 *  batch modify .reviewboard
 *  #2[android][fix bug]delete unsupported tests in android


## 0.2.8 (Fri Feb 28 2014)


 *  CB-5980 Updated version and RELEASENOTES.md for release 0.2.8
 *  [CB-3208] FFOS docs updated
 *  CB-4590 - chooseContact in CDVContacts crashes app
 *  Delete stale test/ directory
 *  CB-5719 Incremented plugin version on dev branch.
 *  * FirefoxOS quirks updated * name.formatted constructed with respect to honorific pre- and suffix
 *  added readOnly formatted field
 *  explanation about organizations added
 *  added organizations and categories
 *  addresses added to the Proxy
 *  refactoring * update from Mozilla moved to Contact prototype * some comments added/modified
 *  search if contact does exist before remove
 *  check for id in the right way
 *  fixed update contacts (if id is provided one needs to search for the contact) updateFromCordova moved to prototype of mozContact fields are fixed the right search is used
 *  wrong example given
 *  docs added
 *  FxOS name fields are arrays hackedSearch refactored search based on find commented out
 *  search added - no idea if this is working
 *  search hacked via getAll
 *  createMozillaFromCordova and vice versa are used to translate contact objects from one API to another.
 *  add/remove working
 *  save is working
 *  attempt to save is failing trying to limit the translated contact fields to name and familyName, but still failing
 *  save is linked with the proxy contact.name doesn't exist www/Contact.js#Contact.prototype.save check on which side is the error


## 0.2.9 (Wed Mar 19 2014)


 *  [iOS] Fixed the problem that failed to retrieve contact's phone number.
 *  [Android]Add choose contact function
 *  Incremented plugin version on dev branch to 0.2.9-dev


## 0.2.10 (Thu Apr 03 2014)


 *  issue 1 contacts-->chooseContact: displayed name is descending. Solution:modify test page
 *  Incremented plugin version on dev branch to 0.2.10-dev


## 0.2.11 (Tue Apr 29 2014)


 *  CB-6452 Updated version and RELEASENOTES.md for release 0.2.10
 *  CB-6460: Update license headers
 *  Windows 8 - added some more #Quirks info
 *  Update docs with Windows 8 support info, fix contacts.find example error
 *  CB-1291 Windows8 supports multiple, added some error checking, converts Windows8 Contact to Cordova Contact
 *  CB-1291 Windows8 added some contact conversion, console.error on save because it is not supported
 *  CB-1291 Windows8 Adding contact picker apis
 *  CB-6126 [BlackBerry10] Update docs quirks section for fields which are supported
 *  CB-6212 iOS: fix warnings compiled under arm64 64-bit
 *  CB-6212 iOS: fix warnings compiled under arm64 64-bit
 *  manually merging CB-3208
 *  Add NOTICE file
 *  Add NOTICE file
 *  CB-6114 Incremented plugin version on dev branch.
 *  CB-6114 Updated version and RELEASENOTES.md for release 0.2.9
 *  CB-6086 Fix typo in ffos part of plugin.xml: Camera -> Contacts
 *  CB-5980 Incremented plugin version on dev branch.
 *  CB-5980 Updated version and RELEASENOTES.md for release 0.2.8
 *  CB-5994 Switch Contact ID lookup to use Raw contact id.
 *  issue 4 contacts->get phone's contacts: full name didn't display right in test page.Bug reason: contact.displayName isn't used. Solution: Use contact.displayName in test page
 *  Incremented plugin version on dev branch to 0.2.11-dev
