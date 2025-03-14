---
title: Extension resource types
description: Lists the Azure resource types are used to extend the capabilities of other resource types.
ms.topic: conceptual
ms.date: 04/19/2022
---

# Resource types that extend capabilities of other resources

An extension resource is a resource that adds to another resource's capabilities. For example, resource lock is an extension resource. You apply a resource lock to another resource to prevent it from being deleted or modified. It doesn't make sense to create a resource lock by itself. An extension resource is always applied to another resource.

## Microsoft.Advisor

* advisorScore
* configurations
* recommendations
* suppressions

## Microsoft.AlertsManagement

* alerts

## Microsoft.Authorization

* accessReviewHistoryDefinitions
* denyAssignments
* eligibleChildResources
* locks
* policyAssignments
* policyDefinitions
* policyExemptions
* policySetDefinitions
* privateLinkAssociations
* roleAssignmentApprovals
* roleAssignments
* roleAssignmentScheduleInstances
* roleAssignmentScheduleRequests
* roleAssignmentSchedules
* roleDefinitions
* roleEligibilityScheduleInstances
* roleEligibilityScheduleRequests
* roleEligibilitySchedules
* roleManagementPolicies
* roleManagementPolicyAssignments

## Microsoft.Automanage

* configurationProfileAssignmentIntents
* configurationProfileAssignments

## Microsoft.Billing

* billingPeriods
* billingPermissions
* billingRoleAssignments
* billingRoleDefinitions
* createBillingRoleAssignment

## Microsoft.Blueprint

* blueprintAssignments
* blueprints

## Microsoft.ChangeAnalysis

* changes
* changeSnapshots
* computeChanges

## Microsoft.Chaos

* artifactSetDefinitions
* artifactSetSnapshots
* chaosProviderConfigurations
* chaosTargets
* targets

## Microsoft.Consumption

* AggregatedCost
* Balances
* Budgets
* Charges
* CostTags
* credits
* events
* Forecasts
* lots
* Marketplaces
* Pricesheets
* products
* ReservationDetails
* ReservationRecommendationDetails
* ReservationRecommendations
* ReservationSummaries
* ReservationTransactions

## Microsoft.ContainerInstance

* serviceAssociationLinks

## Microsoft.CostManagement

* Alerts
* BenefitRecommendations
* BenefitUtilizationSummaries
* Budgets
* Dimensions
* Exports
* ExternalSubscriptions
* Forecast
* GenerateDetailedCostReport
* Insights
* Pricesheets
* Publish
* Query
* Reportconfigs
* Reports
* ScheduledActions
* Views

## Microsoft.CustomProviders

* associations

## Microsoft.DataMigration

* DatabaseMigrations

## Microsoft.DataProtection

* backupInstances

## Microsoft.Diagnostics

* apollo
* insights
* solutions

## Microsoft.EventGrid

* eventSubscriptions
* extensionTopics

## Microsoft.GuestConfiguration

* guestConfigurationAssignments

## Microsoft.HybridConnectivity

* endpoints

## microsoft.insights

* dataCollectionRuleAssociations
* diagnosticSettings
* diagnosticSettingsCategories
* eventtypes
* extendedDiagnosticSettings
* guestDiagnosticSettingsAssociation
* logDefinitions
* logs
* metricbaselines
* metricDefinitions
* metricNamespaces
* metrics
* myWorkbooks
* topology
* transactions

## Microsoft.IoTSecurity

* sensors
* sites

## Microsoft.KubernetesConfiguration

* extensions
* fluxConfigurations
* namespaces
* sourceControlConfigurations

## Microsoft.Maintenance

* applyUpdates
* configurationAssignments
* updates

## Microsoft.ManagedIdentity

* Identities

## Microsoft.ManagedServices

* registrationAssignments
* registrationDefinitions

## Microsoft.Network

* networkManagerConnections

## Microsoft.PolicyInsights

* attestations
* eventGridFilters
* policyEvents
* policyStates
* policyTrackedResources
* remediations

## Microsoft.Quota

* quotaRequests
* quotas
* usages

## Microsoft.RecoveryServices

* backupProtectedItems

## Microsoft.ResourceHealth

* childResources
* events
* impactedResources

## Microsoft.Resources

* links
* tags

## Microsoft.Security

* adaptiveNetworkHardenings
* advancedThreatProtectionSettings
* antiMalwareSettings
* assessmentMetadata
* assessments
* Compliances
* dataCollectionAgents
* deviceSecurityGroups
* InformationProtectionPolicies
* insights
* jitPolicies
* secureScoreControls
* secureScores
* serverVulnerabilityAssessments
* sqlVulnerabilityAssessments

## Microsoft.SecurityInsights

* aggregations
* alertRules
* alertRuleTemplates
* automationRules
* bookmarks
* cases
* dataConnectors
* enrichment
* entities
* entityQueryTemplates
* fileImports
* incidents
* metadata
* MitreCoverageRecords
* onboardingStates
* securityMLAnalyticsSettings
* settings
* sourceControls
* threatIntelligence

## Microsoft.SerialConsole

* serialPorts

## Microsoft.ServiceLinker

* dryruns
* linkers

## Microsoft.SoftwarePlan

* hybridUseBenefits

## Microsoft.Subscription

* policies

## microsoft.support

* supporttickets

## Microsoft.WorkloadMonitor

* monitors

## Next steps

- To get the resource ID for an extension resource in an Azure Resource Manager template, use the [extensionResourceId](../templates/template-functions-resource.md#extensionresourceid).
- For an example of creating an extension resource in a template, see [Event Grid Event Subscriptions](/azure/templates/microsoft.eventgrid/2019-06-01/eventsubscriptions).
