# ELEVATE_LABS-_TASK 2 <br></br><br></br>
Task 2: Analyse a Phishing Email Sample.<br></br><br></br>
Key Concepts: Phishing, email spoofing, header analysis, social engineering, threat detection<br></br>
Objective: Identify phishing characteristics in a suspicious email sample.<br></br>
Tools: MX Lookup, VirusTotal.<br></br><br></br>

----------------------------------------------------------------------------------------------------------------------<br></br>
1.Obtain a sample phishing email (many free samples online).<br></br><br></br>
Email Body Summary:<br></br>
A fake job alert pretending to be a recruiter,<br></br>
-	Urging: To apply for new job role by giving a limited time to become a talented top applicant.<br></br>
-	No phishing alert was triggered.<br></br>
-	Message was sent by "Unknown".<br></br>
-	Urging the user to send CV "To Apply". <br></br>

<br></br>--------------------------------------------------------------------------------------------------------------<br></br>
2.Examine sender's email address for spoofing.
  - Not found<br></br>


<br></br>--------------------------------------------------------------------------------------------------------------<br></br>
3.Check email headers for discrepancies (using online MX Lookup).<br></br><br></br>
Deliverables: A report listing phishing indicators found<br></br>
•	Full email id of sender?<br></br>
    </br> - 194.25.134.82 <br></br>
•	What domain is used to send this mail? (Return path/ From)<br></br>
    </br>-	wilfrid-adam@t-online.de <br></br>
•	Sender IP address blacklisted or not? (VirusTotal, MX Lookup)<br></br>
   </br>-	IP address is not flagged or blacklisted yet.<br></br>

•	What is the status of SPF Authentication Result?<br></br>

  </br> SPF Status  and it's	Description<br></br>
------------------------------------------<br></br>
   </br> pass - The sending IP is authorized by the domain's SPF record. This is a successful SPF check.<br></br>
   </br> fail - The sending IP is not authorized to send on behalf of the domain. Usually triggers rejection or spam filtering.<br></br>
   </br> softfail	- The IP is probably not authorized. The domain's SPF record includes a ~all mechanism (soft fail). Treated as suspicious, but usually not rejected outright.<br></br>
    </br>neutral	- No explicit authorization result. The domain's SPF record uses? all. Mail may still be accepted.<br></br>
   </br> none	- The domain has no SPF record. No authentication was possible.<br></br>
   </br> permerror -	Permanent error in the SPF record (e.g. syntax error). SPF cannot be evaluated.<br></br>
   </br> temperror	- Temporary error (e.g. DNS lookup failure). SPF check could not complete. Retry may succeed later.<br></br>

 </br>SPF (Sender Policy Framework) to authenticate sender mail exchange server Ip address to avoid spam. If the result is pass then it has designated client id or they might have used new legitimate email id and hasn’t been blacklisted yet.<br></br>

•	Is anything suspicious found in the email?<br></br>
   </br>-	Yes<br></br>
   </br>-	Dkim Signature Error: No DKIM-Signature header found<br></br>
  </br> -	Dkim Signature Error: There must be at least one aligned DKIM-Signature for the message to be considered aligned.<br></br>

<br></br>--------------------------------------------------------------------------------------------------------------<br></br>
4.Identify suspicious links or attachments.<br></br>
   </br> - Not Found<br></br>

<br></br>--------------------------------------------------------------------------------------------------------------<br></br>
5.Look for urgent or threatening language in the email body.<br></br><br></br>
   </br>- Yes, urging to apply for new job role by giving a limited time to become a talented top applicant.<br></br>
<br></br>--------------------------------------------------------------------------------------------------------------<br></br>
6.Note any mismatched URLs (hover to see real link).<br></br><br></br>
  </br> - No<br></br>
<br></br>--------------------------------------------------------------------------------------------------------------<br></br>
7.Verify presence of spelling or grammar errors.<br></br><br></br>
  </br> - Not many grammatical mistakes, but lacks authenticity of the job recruiter’s id.<br></br>
<br></br>--------------------------------------------------------------------------------------------------------------<br></br>
8.Summarize phishing traits found in the email.<br></br><br></br>
  </br> - Using legitimate new email id that hasn’t been blacklisted to avoid getting blocked or filtered. No Personalization, no name, user ID, or specific reference is used — shows it's a mass-mailed phishing attempt.<br></br>
<br></br>--------------------------------------------------------------------------------------------------------------<br></br>
Conclusion:<br></br><br></br>
-----------<br></br><br>
This email shows clear signs of phishing:<br></br>
   </br>- Not an authenticated sender identity<br></br>
  </br> - Urgent content.<br></br>
  </br> - Misleading content to gain personal information.<br></br>
   </br>- Lack of personalization<br></br>
  </br> - Signature failure (DKIM)<br></br>

<br></br>--------------------------------------------------------------------------------------------------------------<br></br>
Action Recommended:<br></br><br></br>
----------------------------<br></br>
  </br> - Do NOT send your personal information (CV) in the given id in the email.<br></br>
  </br> - Report the email to your IT/Security team or email provider.<br></br>
  </br> - Mark it as "Phishing" or "Spam" in your email client.<br></br>
<br></br>
<br></br>


<br></br>--------------------------------------------------------------------------------------------------------------<br></br><br></br>
Thank you.<br></br><br></br>
END
<br></br>---------------------------------------------------------------------------------------------------------------<br></br>
<br></br>---------------------------------------------------------------------------------------------------------------<br></br>

