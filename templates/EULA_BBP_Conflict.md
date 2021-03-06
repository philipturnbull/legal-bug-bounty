I’ve expanded in my paper, talks and #legalbugbounty project on this problem of having conflicting contractual terms in the BBP policy that stand in tension with the DMCA exemption, CFAA authorization/safe harbor and DOJ’s framework, and the all idea of conducting a bug bounty in general. This is the unclear habit of subjecting hackers, explicitly in the bug bounty policy, to the end-user-license agreements (EULAs) that further prohibit reverse engineering and other tinkering or researching tools fundamental to security research—and sometimes even prohibit the mere attempt to gain unauthorized access. Instead of granting researchers permission to take such actions, the bug bounty terms prohibit them from doing so under contract, thereby undermining the DMCA exemption for security research and the DOJ framework purposes and basically creating de-facto liability for the researcher – by revoking authorization and sending mixed signals.

I see the logic of clarifying in the bug bounty policy that the other applicable agreements still apply. What I ask is: 
1. Be mindful of this conflict. 
2. Either you curve out the anti-hacking language or clarify that the BBP policy will prevail in case of conflict.

Here is a great example: 

> The Bug Bounty Terms [use a term you previously defined] supplement the terms our [X] User Agreement [With Hyperlink], [Y] Agreement [With Hyperlink] with you [collectively the “Agreements”]. The terms of those Agreements will apply to your use and participation in our Bug Bounty Program. If any inconsistency exists between the terms of such Agreements and the Bug Bounty Terms, the Bug Bounty Terms will prevail with respect to your participation in the Bug Bounty Program.
 
**Note:** Please don’t just say “and any other agreement in which you have entered with [our company]” but actually list and hyper-link these agreements, if possible, if you really want (and you want) the hunter to read them (again, simplify disclosures).

**Attribution:** PayPal is the first company I’ve seen doing this properly, and @LegalRobot asked I will add this to this project. 

## ⚖ Legal disclaimer

**⚠ You must consult with a lawyer before implementing any language!**

This report does not constitute legal advice and the author is not admitted to practice law in the U.S. The information contained herein is for general guidance on matters of interest only. The application and impact of laws can vary widely based on the specific facts involved. Given the changing nature of laws, terms, rules and regulations, there may be delays, omissions or inaccuracies in information contained herein. Accordingly, the information is provided with the understanding that the author is not herein engaged in rendering legal or other professional advice and services. As such, it should not be used as a substitute for consultation with professional legal or other competent advisers. Before making any decision or taking any action, you should consult a professional. All information is provided “as is”, with no guarantee of completeness, accuracy, timeliness or of the results obtained from the use of this information, and without warranty of any kind, express or implied, including, but not limited to warranties of performance, merchantability and fitness for a particular purpose. In no event will the author be liable to you or anyone else for any decision made or action taken in reliance on the information herein or for any consequential, special or similar damages.
