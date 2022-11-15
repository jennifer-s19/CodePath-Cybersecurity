# Honeypot Assignment

**Time spent:** **6** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** How did you deploy it? Did you use GCP, AWS, Azure, Vagrant, VirtualBox, etc.?
GCP

<img src="mhn-admin.gif">

### Dionaea Honeypot Deployment (Required)

**Summary:** Briefly in your own words, what does dionaea do?
dionaea is honeypot that attracts other computers to attack it so dionaea can gain entry/information about the attacking computer.

<img src="dionaea-honeypot.gif">

### Database Backup (Required)

Followed directions to export and download the session.json file. Located in the repo.

**Summary:** What is the RDBMS that MHN-Admin uses? What information does the exported JSON file record?
MHN-Admin uses MongoDB as the RDBMS.
The exported JSON file records the attack data.

_Be sure to upload session.json directly to this GitHub repo/branch in order to get full credit._

### Deploying Additional Honeypot(s) (Optional)

#### X Honeypot

**Summary:** What does this honeypot simulate and do for a security researcher?

<img src="x-honeypot.gif">

### Malware Capture and Identification (Optional)

#### X Malware

**Summary:** How did you find it? Which honeypot captured it? What does each malware do?

MD5 Hash: _Run `md5sum` on the file and record the hash here._

SHA1 Hash: _Run `sha1sum` on the file and record the hash here._

<img src="x-malware.gif">

## Notes

Describe any challenges encountered while doing the assignment:

- issues running the same commands over again to record
- issues trying to figure out which terminal to put the commands in
- issues downloading/exporting the session.json file
