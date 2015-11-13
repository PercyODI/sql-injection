#<center>Print Resources</center>

##Books
- SQL Injection attacks and defense
    - By Justin Clarke, 2012
    - [Permalink](http://missouri.summon.serialssolutions.com/#!/search?bookMark=ePnHCXMw42LgTQStzc4rAe_hAm1sNgQ1Wi0tgWmJGc4xA7UyuIxAWzcNQVU0G4Oov7OvIahlCStFLc2AlQkHbLwEyudkMA8O9FHIzMsCr1TKU0gsKQFtRlcA9rsVUlLTgH2_VIVoxBUyCkXQUfBYbgZFN9cQZw9dYPiBhDLjoQMk8UmWoF6NmWWFMTeDJkRNYnE2sIwBlj8lxfFlOeB5y-J40PFQMK-Ajg1VhqgFVjFFibkpmengWz4KIIdExINufzEEXcerBFEFmQaGS5dUlMSDrti1MDUB3awgh1URkgK4KYitUXBllsB8ZGGBcBBkvhUhjeZswsEAAGkEh2k)
        - Publicized Security Breaches
            - In February 2002, Jeremiah Jacks (www.securityfocus.com/news/346) discovered that Guess.com was vulnerable to SQL injection. He gained access to at least 200,000 customers’ credit card details.
            - In June 2003, Jeremiah Jacks struck again, this time at PetCo.com (www.securityfocus.com/news/6194), where he gained access to 500,000 credit card details via an SQL injection flaw.
            - On June 17, 2005, MasterCard alerted some of its customers to a breach in the security of Card Systems Solutions. At the time, it was the largest known breach of its kind. By exploiting an SQL injection flaw (www.ftc.gov/os/caselist/0523148/0523148complaint.pdf), a hacker gained access to 40 million credit card details.
            - In December 2005, Guidance Software, developer of EnCase, discovered that a hacker had compromised its database server via an SQL injection flaw (www.ftc.gov/os/caselist/0623057/0623057complaint.pdf), exposing the financial records of 3800 customers.
            - Circa December 2006, the US discount retailer TJX was successfully hacked and the attackers stole millions of payment card details from the TJX databases.
            - In August 2007, the United Nations Web site (www.un.org) was defaced via SQL injection vulnerability by an attacker in order to display anti-US messages (http://news.cnet.com/8301-10784_3-9758843-7.html).
            - In 2008, the Asprox botnet leverages SQL injection flaws for mass drive by malware infections in order to grow its botnet (http://en.wikipedia.org/wiki/Asprox). The number of exploited Web pages is estimated at 500,000.
            - In February 2009, a group of Romanian hackers in separate incidents allegedly broke into Kaspersky, F-Secure, and Bit-Defender Web sites by use of SQL injection attacks. The Romanians went on to allegedly hack many other high profile Web sites such as RBS WorldPay, CNET.com, BT.com, Tiscali.co.uk, and national-lottery.co.uk.
            - On August 17, 2009, the US Justice Department charged an American citizen Albert Gonzalez and two unnamed Russians with the theft of 130 million credit card numbers using a SQL injection attack. Among the companies compromised were credit card processor Heartland Payment Systems, convenience store chain 7-Eleven, and supermarket chain Hannaford Brothers.
            - In February 2011, hbgaryfederal.com was found by the Anonymous group to be vulnerable to a SQL injection flaw within its CMS.
            - In April 2011, Barracuda Networks Web site (barracudanetworks.com) was found to be vulnerable to SQL injection and the hacker responsible for the compromise published database dumps online—including the authentication credentials and hashed passwords for CMS users!
            - In May 2011, LulzSec compromised several Sony Web sites (sonypictures.com, SonyMusic.gr, and SonyMusic.co.jp) and proceeded to dump the database contents online for their amusement. LulzSec says it accessed the passwords, e-mail addresses, home addresses and dates of birth of one million users. The group says it also stole all admin details of Sony Pictures, including passwords. 75,000 music codes and 3.5 million music coupons were also accessed, according to the press release.
            - In May 2011, LulzSec compromised the Public Broadcast Service (PBS) Web site—in addition to dumping numerous SQL databases through a SQL injection attack, LulzSec injected a new page into PBS’s Web site. LulzSec posted usernames and hashed passwords for the database administrators and users. The group also posted the logins of all PBS local affiliates, including their plain text passwords.
            - In June 2011, Lady Gaga’s fan site was hacked and according to a statement released at the time “The hackers took a content database dump from www.ladygaga.co.uk and a section of e-mail, first name, and last name records were accessed. There were no passwords or financial information taken”—http://www.mirror.co.uk/celebs/news/2011/07/16/lady-gaga-website-hacked-and-fans-details-stolen-115875-23274356.

##Web Articles
- http://readwrite.com/2011/09/12/report_your_companys_web_apps_are_actually_gaping
- http://readwrite.com/2011/09/13/a-brief-history-of-sql-injecti
- http://www.hpenterprisesecurity.com/collateral/report/CyberSecurityRisksReport.pdf
    - Timeline
        - 1998—Rain Forest Puppy (RFP) discloses/discusses the initial idea of SQL Injection in Phrack Magazine (Volume 9, Issue 54)
        - 2000—SQL Injection FAQ—Chip Andrews—uses the first public usage of term “SQL Injection” in a paper
        - 2003—The idea of blind SQL Injection is disclosed/discussed
        - 2006—Web application vulnerability disclosure skyrockets in part due to SQL Injection
        - 2008—SQL Injection vulnerability disclosure peaks
        - 2008—The Asprox botnet leverages SQL Injection for mass drive by SQLi attacks to grow botnet (http://en.wikipedia.org/wiki/Asprox). From at least April through August, a sweep of attacks began exploiting the SQL Injection vulnerabilities of Microsoft’s IIS Web server and SQL Server database server. The attack does not require guessing the name of a table or column, and it corrupts all text columns in all tables in a single request. An HTML string that references a malware JavaScript file is appended to each value. When that database value is later displayed to a website visitor, the script attempts several approaches at gaining control over a visitor’s system. The number of exploited Web pages is estimated at 500,000.
        - On August 17, 2009, the U.S. Justice Department charged an American citizen Albert Gonzalez and two unnamed Russians with the theft of 130 million credit card numbers using a SQL Injection attack. In reportedly “the biggest case of identity theft in American history,” the man stole cards from a number of corporate victims after researching their payment processing systems. Among the companies hit were credit card processor Heartland Payment Systems, convenience store chain 7-Eleven, and supermarket chain Hannaford Brothers.
        - On February 5, 2011, HBGary, a technology security firm, was broken into by Anonymous using a SQL Injection in their CMS-driven website.
        - On April 11, 2011, Barracuda Networks was compromised using a SQL Injection flaw. Email addresses and usernames of employees were among the information obtained.
        - On June 1, 2011, “hacktivists” of the group LulzSec were accused of using SQLi to steal coupons and to download keys and passwords that were stored in plaintext on Sony’s website, accessing the personal information of a million users.
        - In June 2011, Group Anonymous claims to have hacked the NATO site, using a “simple SQL Injection.

##Historic Documents
- [NT Web Technology Vulnerabilities](http://phrack.org/issues/54/8.html#article)
    - By rain.forrest.puppy
    - First documentation of SQL Injection