pageTitle="CloudKnox Experience Blockers"
description="CloudKnox Experience Blockers"
ms.author="ChasityMSFT"
selfHelpType="problemScopingQuestion"
supportTopicIds="32827879,32827857,32827880,32827858,32827872,32827876,32827878,32827867,32827855,32827856,32827870,32827854,32827853,32827861,32827848,
32827849,32827863,32827873,32827850,32827851,32827852,32827859,32827871,32827860,32827881,32827862,32827865,32827868,32827864,32827877,32827866,
32827869,32827874,32827875"
productPesIds="17740"
cloudEnvironments="public"
articleId="problemscopingques-cloudknoxexperienceblockers"
	ownershipId="AzureIdentity_AppProxy"

// # CloudKnox Experience Blockers scoping questions
// ---
{
	 "$schema": "SelfHelpContent",
	  "subscriptionRequired": true,
	  "resourceRequired": true,
		"title": "CloudKnox Experience Blockers",
		"fileAttachmentHint": "",
		"formElements": [{
			"id": "complete_data collection",
			"visibility": "null",
			"order": 1,
			"controlType": "dropdown",
			"infoBalloonText": "",
			"displayLabel": "Have you already completed data collection?",
			"watermarkText": "Choose an option",
			"dropdownOptions": [{
				"value": "Yes",
				"text": "Yes"
			}, {
				"value": "No",
				"text": "No"
			}, {
				"value": "I don't know",
				"text": "I don't know"
			}],
			"required": true
		}, {
				"id": "cloud_collect",
				"visibility": "complete_data collection == Yes",
				"order": 2,
				"controlType": "multiselectdropdown",
				"infoBalloonText": "",
				"displayLabel": "On which clouds?",
				"watermarkText": "Select all that apply",
				"dropdownOptions": [{
					"value": "AWS",
					"text": "AWS"
				}, {
					"value": "Azure",
					"text": "Azure"
				}, {
					"value": "GCP",
					"text": "GCP"
				}],
				"required": false
			},  {
				"id": "access",
				"visibility": "null",
				"order": 3,
				"controlType": "dropdown",
				"infoBalloonText": "",
				"displayLabel": "Are you open to giving us 'Master Account' (AWS), Management Group (Azure) and/or Folder (GCP) access?",
				"watermarkText": "Choose an option",
				"dropdownOptions": [{
					"value": "Yes",
					"text": "Yes",
				}, {
					"value": "No",
					"text": "No"
				}],
			"required": true
			}, {
				"id": "full remediation",
				"visibility": "null",
				"order": 4,
				"controlType": "dropdown",
				"infoBalloonText": "",
				"displayLabel": "Do you plan on doing full remediation using CloudKnox during our Public Preview?",
				"watermarkText": "Choose an option",
				"dropdownOptions": [{
					"value": "Yes",
					"text": "Yes"
				}, {
					"value": "No",
					"text": "No"
					}
				],
				"required": true
				},  {
				"id": "issues",
				"visibility": "null",
				"order": 5,
				"controlType": "multiselectdropdown",
				"infoBalloonText": "",
				"displayLabel": "If you are having issues, where are you blocked in CloudKnox Permissions Management product use?",
				"watermarkText": "Select all that apply",
				"dropdownOptions": [{
						"value": "Dashboard",
						"text": "Dashboard"
					}, {
						"value": "Analytics",
						"text": "Analytics"
					}, {
						"value": "Remediation",
						"text": "Remediation"
					}, {
						"value": "Notifications",
						"text": "Notification"
					}, {
						"value": "Reports",
						"text": "Reports"
					}, {
						"value": "Audit",
						"text": "Audit"
					}, {
						"value": "Users",
						"text": "Users"
					}, {
						"value": "Help",
						"text": "Help"
					}, {
						"value": "Other",
						"text": "Other"
					}, 
				],
				"required": false
			} ]
		}