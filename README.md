# WSO2-2021-1260: Deletion of Arbitrary files via Path Traversal in Artifact Name in WSO2 ESB

Due to the unsanitized user input in the Artifact Upload feature, an arbitrary file deletion attack could be carried out by leveraging path traversal in the "artifactName" parameter.

### Vendor Disclosure:

The vendor's disclosure and fix for this vulnerability can be found [here](https://security.docs.wso2.com/en/latest/security-announcements/security-advisories/2021/WSO2-2021-1260/).

### Why no CVE?

Neither me nor the vendor requested a CVE for this vulnerability.

### Requirements:

This vulnerability requires:
<br/>
- Valid user credentials

### Proof Of Concept:

More details and the exploitation process can be found in this [PDF](https://github.com/mbadanoiu/WSO2-2021-1260/blob/main/WSO2%20ESB%20-%20WSO2-2021-1260.pdf).

