COLLECT EMAIL ADRESS VERIFIED

GOOGLE DESCRIPTION

Please enter your full name.
 
GOOGLE FORM SCRIPT 

function sendEmails() {
  var emailAddress = "joren@gmail.com"; // Make sure to provide the complete email address
  var subject = "Good morning!";
  var currentTime = new Date();
  var formattedTime = currentTime.toLocaleString('en-US', { timeZone: 'Asia/Manila', hour12: true });

  // Get the name from the form responses
  var formResponses = FormApp.getActiveForm().getResponses();
  var latestResponse = formResponses[formResponses.length - 1];
  var name = latestResponse.getItemResponses()[0].getResponse();

  // Compose the email body
  var emailBody = "Hello There!<br><br>I am pleased to inform you that your child " + name + " from 12 TVL N - MAAASAHAN, has safely arrived on the school premises on " + formattedTime + ".";
  
  // Send email
  GmailApp.sendEmail(emailAddress, subject, "", { htmlBody: emailBody });
}


GOOGLE SHEET SCRIPT (TVL N MAASAHAN)

function onFormSubmit(e) {
  var spreadsheetId = "16FO3Kh6BGUjouxpTZtD2JY8g6v9vxZhvcQmhpeOhn6k";
  var secondSheet = SpreadsheetApp.openById(spreadsheetId).getActiveSheet();
  
  secondSheet.appendRow(e.values);
}

GOOGLE SHEET SCRIPT (TVL A)

function onFormSubmit(e) {
  var spreadsheetId = "1k4VMi7IbGZB5JZqmOoiogq7ipRvUdqXC4JrXsC671wY";
  var secondSheet = SpreadsheetApp.openById(spreadsheetId).getActiveSheet();
  
  secondSheet.appendRow(e.values);
}

GOOGLE SHEET SCRIPT (12 TVL A MAKADIYOS)

function onFormSubmit(e) {
  var spreadsheetId = "1X65CFivIS68DiwqmPK3gd-RWfmz7TNwIIfXB-3pM8GM";
  var secondSheet = SpreadsheetApp.openById(spreadsheetId).getActiveSheet();
  
  secondSheet.appendRow(e.values);
}


MAGKAHIWALAY YUNG MAIN ATTENDANCE DATABASE NUNG g11 AT g12


Emmanuel Samar

https://docs.google.com/forms/d/e/1FAIpQLSdMVMftOVUKHiB5go3Bh57HKWf2bM1E36X2ArnEjcvToe4s8Q/viewform?usp=pp_url&entry.1292892985=+Emmanuel+Benidick+Samar+

Mc Joe Cyrel D. Realingo

https://docs.google.com/forms/d/e/1FAIpQLSfRC35qUlIxyrpImBH__B7NKsbyoKY0CLWjvRTlvCU9Yp1oDg/viewform?usp=pp_url&entry.101341715=Mc+Joe+Cyrel+D.+Realingo

Abigaile Tenebro

https://docs.google.com/forms/d/e/1FAIpQLScPKrL0uEtv0QrsrMsAksG_JyUQWNanZNvVSs2dwpnIHySG6A/viewform?usp=pp_url&entry.647463054=Abigaile+Tenebro

Arocha, Charlie

https://docs.google.com/forms/d/e/1FAIpQLSfuB0DyG8lwCQNKX22rpYSrkWm8vhzapjAKEMTsMbKfHU0_eQ/viewform?usp=pp_url&entry.577181392=Arocha,+Charlie

Callos, Kathlen Mae L.

https://docs.google.com/forms/d/e/1FAIpQLScYuH60NTiJK8gXYIS51BCSO_BBC_pPGKKk6kquFOP6BSvaCQ/viewform?usp=pp_url&entry.25231534=Callos,+Kathlen+Mae+L.

Carl Jhon Bañadera

https://docs.google.com/forms/d/e/1FAIpQLSc1u9Igg5w0T5UX5YGYQYO3woruvDBBAwbW2G6fE_Shxqj6kA/viewform?usp=pp_url&entry.1218966442=Carl+Jhon+Ba%C3%B1adera

Dan Marius O. Abug

https://docs.google.com/forms/d/e/1FAIpQLSdUqiHRjLdAPOLmIqeXk_9YpH2xY6DfaejqZOam-Q1l7idJoA/viewform?usp=pp_url&entry.1989684809=Dan+Marius+O.+Abug

EMAAS, JOHN KENNETH R.

https://docs.google.com/forms/d/e/1FAIpQLSdp6_l84YKsNOxW-Ppg-oT0WRW3qZN9ZAsO57pz_XHpb5UT9A/viewform?usp=pp_url&entry.1900211526=EMAAS,+JOHN+KENNETH+R.

Espiritu Miyuki Sherylyn 

https://docs.google.com/forms/d/e/1FAIpQLScluC2quU3guJflubA__WA0i20U1-A574a8bU_UFZYgt-xhKw/viewform?usp=pp_url&entry.856487101=Espiritu+Miyuki+Sherylyn+

General, Marie Joyce C.

https://docs.google.com/forms/d/e/1FAIpQLScC2vERCqInqWlbHAsc2Bnzk_cg58BLT6sqvBocOPvoxnumAg/viewform?usp=pp_url&entry.1297948401=General,+Marie+Joyce+C.

Gian Franco L. Garcia

https://docs.google.com/forms/d/e/1FAIpQLScOlnTPuhf1vHiIg4zvxRFFXURIrsv-d4AV0IoxUzCkscIsIA/viewform?usp=pp_url&entry.1858241555=Gian+Franco+L.+Garcia

Glaiza Marie V. Galapin

https://docs.google.com/forms/d/e/1FAIpQLSf5pdRE8G2QkPD0cOvX1czWJVocqTHHYwyBQo4t-SPfwTf4PA/viewform?usp=pp_url&entry.967550669=Glaiza+Marie+V.+Galapin

Jackielyn Gusto

https://docs.google.com/forms/d/e/1FAIpQLSecnXLe9W7a99_GgGSWP8eJR_KGd0-mHneOR2h4CVmCh4aU3Q/viewform?usp=pp_url&entry.1558534807=Jackielyn+Gusto

Jhon Francis Pelia

https://docs.google.com/forms/d/e/1FAIpQLSfcOBN354_E2c3RefasNFzApufhuYbqceki2en_xr2Mh_qlfA/viewform?usp=pp_url&entry.1168915916=Jhon+Francis+Pelia

Natalie M. Alienza

https://docs.google.com/forms/d/e/1FAIpQLSczFbkh18XxdqDwlA7nhPoysleqQFpyXMFs4zlVSDTXPrIjYw/viewform?usp=pp_url&entry.548604203=Natalie+M.+Alienza

Nebrao, Chrishan James B.

https://docs.google.com/forms/d/e/1FAIpQLSdbgbM76iBzJxu4hRMnI64Lt4LzJbMvs-Vn85qPxOYHvq-MnQ/viewform?usp=pp_url&entry.2113687127=Nebrao,+Chrishan+James+B.

Nicole Genabe Capuno

https://docs.google.com/forms/d/e/1FAIpQLScQVmqpHfDM6FW9zNJZXCduMDsOEgoZbCfA_Daz2x_013ekcQ/viewform?usp=pp_url&entry.996001045=Nicole+Genabe+Capuno

Precious Myriel D. Napura

https://docs.google.com/forms/d/e/1FAIpQLScAoxTYz4GJfPaFcXZckOKFJkllky-eH2vk8oIry2Ohlivt1w/viewform?usp=pp_url&entry.1289307857=Precious+Myriel+D.+Napura

Princess Jamaicah Colanggo

https://docs.google.com/forms/d/e/1FAIpQLSd1PjFXDBXX9n8NUhEyxoRFGDmCNLj2QsTdDMDD6xWHxFUiSQ/viewform?usp=pp_url&entry.1090629125=Princess+Jamaicah+Colanggo

Pulgado, Tristan Ivan D.

https://docs.google.com/forms/d/e/1FAIpQLScQB7tDPcm9rRaRnlJHTYXBXkciW5Vx_JoVIVwS6FTta2o6ZQ/viewform?usp=pp_url&entry.1694500351=Pulgado,+Tristan+Ivan+D.

Queency Abao

https://docs.google.com/forms/d/e/1FAIpQLSfKkycYQ4WogtYaYUW5XvldCSDEETmmgKdcLKcyX6yGR2lzug/viewform?usp=pp_url&entry.1244137749=Queency+Abao

Rachelle Anne G. Rasco

https://docs.google.com/forms/d/e/1FAIpQLSc6EsMEx7ePKj_hFp7rosklU56wZp-F-hXMG45r7bwLYKi2KQ/viewform?usp=pp_url&entry.1711922283=Rachelle+Anne+G.+Rasco

Raymart Dawal 

https://docs.google.com/forms/d/e/1FAIpQLSe6gxS7KWOq5mhZ_mqRKQO_O8Rpp_TqBMeXSmoiHSGsqK62Wg/viewform?usp=pp_url&entry.1645909100=Raymart+Dawal+

Rysa Esguerra

https://docs.google.com/forms/d/e/1FAIpQLSc1np-4Qc3Szrx52OwF7zkZDIB-Iu_Vbn-LC69KIE8z-spuGQ/viewform?usp=pp_url&entry.127584966=Rysa+Esguerra

Sarah Jean Z. Lestor

https://docs.google.com/forms/d/e/1FAIpQLSem1rkzI0oLWcZnB0pCezDk2qUZRCn_qussXKNLyxI8q4q2GA/viewform?usp=pp_url&entry.1567919955=Sarah+Jean+Z.+Lestor

Shairene G. Gabin

https://docs.google.com/forms/d/e/1FAIpQLSeCAV9AY6P0tPpTF9SwtjjECsWmgrFQYcEsnwMn1QsLS-mTtw/viewform?usp=pp_url&entry.156415749=Shairene+G.+Gabin

Shiela Mae D. Javellana 

https://docs.google.com/forms/d/e/1FAIpQLScp43ZKdhKCECjm37GtawShSv0wPoW8SMrp5OKfuGNuZ1kJ6w/viewform?usp=pp_url&entry.1486062125=Shiela+Mae+D.+Javellana

Shiela Mae M. Paigan

https://docs.google.com/forms/d/e/1FAIpQLSfwVxVS3CiwueRgFtX85e42A0B_zIFxWW9xW8vRYpnOU9dIzQ/viewform?usp=pp_url&entry.893332221=Shiela+Mae+M.+Paigan









