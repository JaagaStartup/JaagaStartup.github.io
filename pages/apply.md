---
layout: page
title: "Apply"
meta_title: "Apply - Jaaga Startup"
subheadline: ""
teaser: ""
permalink: "/apply/"
---

<!-- Note :
   - You can modify the font style and form style to suit your website. 
   - Code lines with comments “Do not remove this code”  are required for the form to work properly, make sure that you do not remove these lines of code. 
   - The Mandatory check script can modified as to suit your business needs. 
   - It is important that you test the modified form before going live.-->
<div id='crmWebToEntityForm' style='width:600px;margin:auto;'>
   <META HTTP-EQUIV ='content-type' CONTENT='text/html;charset=UTF-8'>
   <form action='https://crm.zoho.com/crm/WebToLeadForm' name=WebToLeads2110132000000115188 method='POST' onSubmit='javascript:document.charset="UTF-8"; return checkMandatory()' accept-charset='UTF-8'>

	 <!-- Do not remove this code. -->
	<input type='text' style='display:none;' name='xnQsjsdp' value='ac0a5a33182d0fb92646e4eafbcc26c75b1f951c69a6fc280e519f05b7fb5822'/>
	<input type='hidden' name='zc_gad' id='zc_gad' value=''/>
	<input type='text' style='display:none;' name='xmIwtLD' value='828e80b757aa4c8b51cb28844519012d62dd0c5ceeb0d2153433e984b741336d'/>
	<input type='text' style='display:none;'  name='actionType' value='TGVhZHM='/>

	<input type='text' style='display:none;' name='returnURL' value='http&#x3a;&#x2f;&#x2f;jaagastartup.in&#x2f;cowork&#x2f;' /> 
	 <!-- Do not remove this code. -->
	<input type='text' style='display:none;' id='ldeskuid' name='ldeskuid'></input>
	<input type='text' style='display:none;' id='LDTuvid' name='LDTuvid'></input>
	 <!-- Do not remove this code. -->
	<style>
		tr , td { 
			padding:6px;
			border-spacing:0px;
			border-width:0px;
			}
	</style>
	<table style='width:600px;background-color:white;color:black'>

	<tr><td colspan='2' style='text-align:left;color:black;font-family:Calibri;font-size:15px;'><strong>Join the Jaaga Startup Community</strong></td></tr>

	<tr><td  style='nowrap:nowrap;text-align:left;font-size:13px;font-family:Calibri;width:200px;'>First Name<span style='color:red;'>*</span></td><td style='width:250px;' ><input type='text' style='width:250px;'  maxlength='40' name='First Name' /></td></tr>

	<tr><td  style='nowrap:nowrap;text-align:left;font-size:13px;font-family:Calibri;width:200px;'>Last Name<span style='color:red;'>*</span></td><td style='width:250px;' ><input type='text' style='width:250px;'  maxlength='80' name='Last Name' /></td></tr>

	<tr><td  style='nowrap:nowrap;text-align:left;font-size:13px;font-family:Calibri;width:200px;'>Email<span style='color:red;'>*</span></td><td style='width:250px;' ><input type='text' style='width:250px;'  maxlength='100' name='Email' /></td></tr>

	<tr><td  style='nowrap:nowrap;text-align:left;font-size:13px;font-family:Calibri;width:200px;'>Mobile</td><td style='width:250px;' ><input type='text' style='width:250px;'  maxlength='30' name='Mobile' /></td></tr>

	<tr><td  style='nowrap:nowrap;text-align:left;font-size:13px;font-family:Calibri;width:200px;'>Company</td><td style='width:250px;' ><input type='text' style='width:250px;'  maxlength='100' name='Company' /></td></tr>

	<tr><td  style='nowrap:nowrap;text-align:left;font-size:13px;font-family:Calibri;width:200px;'>Website</td><td style='width:250px;' ><input type='text' style='width:250px;'  maxlength='255' name='Website' /></td></tr>

	<tr><td  style='nowrap:nowrap;text-align:left;font-size:13px;font-family:Calibri;width:200px;'>No. of coworking memberships needed</td><td style='width:250px;' ><input type='text' style='width:250px;'  maxlength='9' name='No of Employees' /></td></tr>

	<tr><td  style='nowrap:nowrap;text-align:left;font-size:13px;font-family:Calibri;width:200px;'>What skills are you willing and able to share&#x3f;<span style='color:red;'>*</span></td><td style='width:250px;'>
		<select style='width:250px;' name='LEADCF1' multiple>
			<option value='Design'>Design</option>
			<option value='Technology'>Technology</option>
			<option value='Sales&#x20;and&#x20;Marketing'>Sales and Marketing</option>
			<option value='Digital&#x20;Marketing'>Digital Marketing</option>
			<option value='Product&#x20;Management'>Product Management</option>
			<option value='Financial&#x20;planning&#x20;and&#x20;funding'>Financial planning and funding</option>
			<option value='Operations&#x20;&#x28;HR,&#x20;legal,&#x20;accounting,&#x20;banking...&#x29;'>Operations &#x28;HR, legal, accounting, banking...&#x29;</option>
		</select></td></tr>

	<tr><td colspan='2' style='text-align:center; padding-top:15px;'>
		<input style='font-size:13px;color:#131307' type='submit' value='Submit' />
		<input type='reset' style='font-size:13px;color:#131307' value='Reset' />
	    </td>
	</tr>
   </table>
	<script>
 	  var mndFileds=new Array('First Name','Last Name','Email','LEADCF1');
 	  var fldLangVal=new Array('First Name','Last Name','Email','What skills are you willing and able to share?');
		var name='';
		var email='';

 	  function checkMandatory() {
		for(i=0;i<mndFileds.length;i++) {
		  var fieldObj=document.forms['WebToLeads2110132000000115188'][mndFileds[i]];
		  if(fieldObj) {
			if (((fieldObj.value).replace(/^\s+|\s+$/g, '')).length==0) {
			 if(fieldObj.type =='file')
				{ 
				 alert('Please select a file to upload.'); 
				 fieldObj.focus(); 
				 return false;
				} 
			alert(fldLangVal[i] +' cannot be empty.'); 
   	   	  	  fieldObj.focus();
   	   	  	  return false;
			}  else if(fieldObj.nodeName=='SELECT') {
  	   	   	 if(fieldObj.options[fieldObj.selectedIndex].value=='-None-') {
				alert(fldLangVal[i] +' cannot be none.'); 
				fieldObj.focus();
				return false;
			   }
			} else if(fieldObj.type =='checkbox'){
 	 	 	 if(fieldObj.checked == false){
				alert('Please accept  '+fldLangVal[i]);
				fieldObj.focus();
				return false;
			   } 
			 } 
			 try {
			     if(fieldObj.name == 'Last Name') {
				name = fieldObj.value;
 	 	 	    }
			} catch (e) {}
		    }
		}
		trackVisitor();
	}
</script><script type='text/javascript' id='VisitorTracking'>var $zoho= $zoho || {salesiq:{values:{},ready:function(){$zoho.salesiq.floatbutton.visible('hide');}}};var d=document;s=d.createElement('script');s.type='text/javascript';s.defer=true;s.src='https://salesiq.zoho.com/null/float.ls?embedname=jaagastartup###null';t=d.getElementsByTagName('script')[0];t.parentNode.insertBefore(s,t);function trackVisitor(){try{if($zoho){var LDTuvidObj = document.forms['WebToLeads2110132000000115188']['LDTuvid'];if(LDTuvidObj){LDTuvidObj.value = $zoho.salesiq.visitor.uniqueid();}var firstnameObj = document.forms['WebToLeads2110132000000115188']['First Name'];if(firstnameObj){name = firstnameObj.value +' '+name;}$zoho.salesiq.visitor.name(name);var emailObj = document.forms['WebToLeads2110132000000115188']['Email'];if(emailObj){email = emailObj.value;$zoho.salesiq.visitor.email(email);}}} catch(e){}}</script>
	</form>
</div>