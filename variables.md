# Variables

## Shared/global context
- Global.RequestType : InfrastructureRequestType
- Global.Country : Text
- Global.Site : Text
- Global.Service : InfrastructureService
- Global.System : Text
- Global.Device : Text
- Global.RequestSummary : Text
- Global.BusinessImpact : Text
- Global.ImpactLevel : ImpactLevel
- Global.Deadline : DateTime
- Global.Requester : Text/Person as implementation permits

## Common workflow variables
- varMissingInformation : Text
- varFindings : Text
- varRecommendedAction : Text
- varOwner : Text
- varApprovalRequired : Boolean
- varStatus : WorkStatus

## Incident
- varSymptoms : Text
- varIncidentStartTime : DateTime
- varUsersAffected : Number/Text
- varRecentChange : Text
- varTroubleshootingDone : Text
- varServiceAvailable : Boolean
- varPossibleCause : Text
- varRootCauseVerified : Boolean
- varEscalationRequired : Boolean

## Installation
- varEquipment : Text
- varManufacturer : Text
- varModel : Text
- varQuantity : Number
- varInstallationLocation : Text
- varSiteReady : Boolean
- varPrerequisites : Text
- varDependencies : Text
- varVendorRequired : Boolean
- varInstallationDate : DateTime
- varChangeRequired : Boolean
- varValidationSteps : Text

## Upgrade
- varCurrentVersion : Text
- varTargetVersion : Text
- varCurrentConfiguration : Text
- varTargetConfiguration : Text
- varUpgradeReason : Text
- varAffectedServices : Text
- varDependencies : Text
- varMaintenanceWindow : Text/DateTime
- varRollbackRequired : Boolean
- varRollbackPlan : Text
- varBackupRequired : Boolean
- varVendorRequired : Boolean
- varValidationPlan : Text

## Change
- varChangeDescription : Text
- varChangeReason : Text
- varAffectedServices : Text
- varImplementationPlan : Text
- varMaintenanceWindow : Text/DateTime
- varExpectedImpact : Text
- varValidationPlan : Text
- varRollbackPlan : Text
- varChangeOwner : Text
- varApprovalRequired : Boolean
- varApprovalStatus : ApprovalStatus
- varProductionChange : Boolean
- varChangeReference : Text

Safety condition: if varProductionChange is true and varApprovalStatus is not Approved, do not execute a production change. Continue only with information, analysis, and planning.

## Vendor coordination
- varVendorName : Text
- varVendorContact : Text
- varVendorAction : Text
- varInternalAction : Text
- varVendorPrerequisites : Text
- varVisitDate : DateTime
- varAccessRequired : Boolean/Text
- varSiteContact : Text
- varDependency : Text
- varWaitingOn : ActionOwner

## Site readiness
- varReadinessPurpose : Text
- varPowerReady : VerificationStatus
- varNetworkReady : VerificationStatus
- varCablingReady : VerificationStatus
- varSpaceReady : VerificationStatus
- varEquipmentDelivered : VerificationStatus
- varAccessReady : VerificationStatus
- varVendorReady : VerificationStatus
- varPrerequisites : Text
- varReadinessStatus : VerificationStatus
- varReadinessGap : Text

## Documentation
- varDocumentationType : DocumentationType
- varSearchQuery : Text
- varProduct : Text
- varVersion : Text
- varKnowledgeResult : Text
- varSourceName : Text
- varSourceVerified : Boolean
- varAnswerFound : Boolean
