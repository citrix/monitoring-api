# Citrix.Monitor.Notifications

##Monitor.Notifications.PowerShell.MonitorNotificationSnmpServerConfiguration
            
Add Summary
        
###Properties

####Id
Unique identifier for the MonitorNotificationRule
####HostName
Server address
####Port
Server port
####Sender
Sender id
####AuthPassword
Whether the server requires authentication
####PrivatePassword
Whether the server requires authentication
####AuthPasswordProtocol
Whether the server requires authentication
####PrivatePasswordProtocol
Whether the server requires authentication
####EngineId
Whether the server requires authentication
####CommunityString
CommunityString is required for V2
####Protocol
CommunityString is required for V2
###Methods


####Constructor
Initializes a new instance of the MonitorNotificationRule class.

####Copy(Citrix.Monitor.Notifications.PowerShell.MonitorNotificationSnmpServerConfiguration)
Copy a PoSH object into a model object

##Monitor.Notifications.PowerShell.MonitorEnumConverter
            
Add Summary
        
###Methods


####StringToParameterType(System.String)
Add Summary

####StringToTargetType(System.String)
Add Summary

####StringToConditionTargetType(System.String)
Add Summary

####StringToActionType(System.String)
Add Summary

####StringToGroupState(System.String)
Add Summary

##Monitor.Notifications.PowerShell.MonitorNotificationActionEmail
            
Add Summary
        
###Properties

####Id

####RuleAction

####Configuration

####EmailAddressList

####CultureName

###Methods


####Constructor
Add Summary

####Copy(Citrix.Monitor.Notifications.PowerShell.MonitorNotificationActionEmail)
Duplicate uninitialized model object for transfer across wire

##Monitor.Notifications.PowerShell.MonitorNotificationConditionDefinition
            

        
###Properties

####Id
Gets or sets the identifier. The identifier.
####Reference
Gets or sets the reference. The reference.
####Parameters
Gets or sets the parameters. The parameters.
####Operation
Gets or sets the operation The operation
####Source
Gets or sets the source. The source.
###Methods


####Constructor
Initializes a new instance of the class.
> #####Parameters
> **notificationConditionDefinition:** The notification condition definition.


##Monitor.Notifications.PowerShell.MonitorNotificationDefinition
            

        
###Properties

####Priority
Gets or sets the priority. The priority.
####Condition
Gets or sets the condition. The condition.
###Methods


####Constructor
Add Summary

##Monitor.Notifications.PowerShell.MonitorNotificationEmailServerConfiguration
            
Add Summary
        
###Properties

####Id
Unique identifier for the MonitorNotificationRule
####Protocol
Mail protocol
####HostName
Server address
####Port
Server port
####Sender
Sender id
####RequiresAuthentication
Whether the server requires authentication
####UserName
Mail UserName
###Methods


####Constructor
Initializes a new instance of the MonitorNotificationRule class.

####Copy(Citrix.Monitor.Notifications.PowerShell.MonitorNotificationEmailServerConfiguration)
Copy a PoSH object into a model object

##Monitor.Notifications.PowerShell.MonitorNotificationRule
            
Add Summary
        
###Properties

####IsAggregate
Should the targets be evaluated in an aggregate or individually?
####Id
Unique identifier for the MonitorNotificationRule
####Enabled
true if enabled; otherwise, false.
####RuleName
Name of MonitorNotificationRule Desktop Director name: do we need this?
####RuleDescription
Description of MonitorNotificationRule
####NotificationTemplateId
TemplateId A string representation of the text Id that references the template in the Rule Template XML file This is not a database foreign key
####NotificationRuleParameters
List of parameters for this MonitorNotificationRule
####NotificationRuleTarget
List of targets for this MonitorNotificationRule
####NotificationRuleActions
List of actions for this MonitorNotificationRule
####NotificationRuleGroupId
Optional group to which this belongs
####RuleTemplate
Add Summary
####
Unique identifier for the NotificationRule
####
Type of NotificationAction
####
Unique identifier for the NotificationRule
####
Name of NotificationRule Desktop Director name: do we need this?
####
Description of NotificationRule
####
Webhook of NotificationRule
####
SNMP Trap is enabled for Policy
####
State of the Notification Group
####
List of rules in the group
####
Unique identifier for the NotificationRule
####
TemplateParameterId A string representation of the text Id that references the template parameter Id in the Rule Template XML file This is not a database foreign key
####
indicates the datatype of the Value attribute
####
string representation of the data for this parameter value
####
foreign key identifier to the NotificationRule explicitly included for PowerPivot functionality
####
Unique identifier for the NotificationRuleTarget
####
Name of NotificationRuleTarget Desktop Director name: do we need this?
####
TargetType
####
foreign key identifier to the NotificationRule explicitly included for PowerPivot functionality
####
List of target values for this NotificationRuleTarget
####
Unique identifier for the NotificationRuleTargetValue
####
Value portion of NotificationRuleTargetValue value pair
####
NotificationRuleTarget object with which this value is associated explicitly included for PowerPivot functionality
###Methods


####Constructor
Initializes a new instance of the MonitorNotificationRule class.

####Copy(Citrix.Monitor.Notifications.PowerShell.MonitorNotificationRule,Citrix.Monitor.Notifications.Interfaces.IRuleTemplate)
Copy a PoSH object into a model object

####Constructor
Initializes a new instance of the MonitorNotificationRuleAction class.

####
Duplicate uninitialized model object for transfer across wire

####Constructor
Add Summary

####
Copy a PoSH object into a model object

####Constructor
Initializes a new instance of the class.

####
Duplicate uninitialized model object for transfer across wire

####Constructor
Add Summary

####
Duplicate uninitialized model object for transfer across wire

####Constructor
Add Summary

####
Copy a PoSH object into a model object

##Monitor.Notifications.PowerShell.MonitorNotificationRuleAction
            
Add Summary
        
###Properties

####Id
Unique identifier for the NotificationRule
####NotificationActionType
Type of NotificationAction
###Methods


####Constructor
Initializes a new instance of the MonitorNotificationRuleAction class.

####Copy(Citrix.Monitor.Notifications.PowerShell.MonitorNotificationRuleAction)
Duplicate uninitialized model object for transfer across wire

##Monitor.Notifications.PowerShell.MonitorNotificationRuleGroup
            
Add Summary
        
###Properties

####Id
Unique identifier for the NotificationRule
####Name
Name of NotificationRule Desktop Director name: do we need this?
####Description
Description of NotificationRule
####Webhook
Webhook of NotificationRule
####IsSnmpEnabled
SNMP Trap is enabled for Policy
####NotificationGroupState
State of the Notification Group
####NotificationRules
List of rules in the group
###Methods


####Constructor
Add Summary

####Copy(Citrix.Monitor.Notifications.PowerShell.MonitorNotificationRuleGroup)
Copy a PoSH object into a model object

##Monitor.Notifications.PowerShell.MonitorNotificationRuleParameter
            
Add Summary
        
###Properties

####Id
Unique identifier for the NotificationRule
####TemplateParameterId
TemplateParameterId A string representation of the text Id that references the template parameter Id in the Rule Template XML file This is not a database foreign key
####NotificationRuleParameterType
indicates the datatype of the Value attribute
####Value
string representation of the data for this parameter value
####NotificationRuleId
foreign key identifier to the NotificationRule explicitly included for PowerPivot functionality
###Methods


####Constructor
Initializes a new instance of the class.

####Copy(Citrix.Monitor.Notifications.PowerShell.MonitorNotificationRuleParameter)
Duplicate uninitialized model object for transfer across wire

##Monitor.Notifications.PowerShell.MonitorNotificationRuleTarget
            
Add Summary
        
###Properties

####Id
Unique identifier for the NotificationRuleTarget
####Name
Name of NotificationRuleTarget Desktop Director name: do we need this?
####NotificationRuleTargetType
TargetType
####NotificationRuleId
foreign key identifier to the NotificationRule explicitly included for PowerPivot functionality
####NotificationRuleTargetValues
List of target values for this NotificationRuleTarget
####
Unique identifier for the NotificationRuleTargetValue
####
Value portion of NotificationRuleTargetValue value pair
####
NotificationRuleTarget object with which this value is associated explicitly included for PowerPivot functionality
###Methods


####Constructor
Add Summary

####Copy(Citrix.Monitor.Notifications.PowerShell.MonitorNotificationRuleTarget)
Duplicate uninitialized model object for transfer across wire

####Constructor
Add Summary

####
Copy a PoSH object into a model object

##Monitor.Notifications.PowerShell.MonitorNotificationRuleTargetValue
            
Add Summary
        
###Properties

####Id
Unique identifier for the NotificationRuleTargetValue
####Value
Value portion of NotificationRuleTargetValue value pair
####NotificationRuleTargetId
NotificationRuleTarget object with which this value is associated explicitly included for PowerPivot functionality
###Methods


####Constructor
Add Summary

####Copy(Citrix.Monitor.Notifications.PowerShell.MonitorNotificationRuleTargetValue)
Copy a PoSH object into a model object

##Monitor.Notifications.PowerShell.MonitorParameterMapping
            

        

##Monitor.Notifications.PowerShell.MonitorRuleTemplate
            
Represents a rule template
        
###Properties

####Id
Gets or sets the identifier. The identifier.
####CultureName
Gets or sets the current culture. The current culture.
####TemplateName
Gets or sets the name of the template. The name of the template.
####TemplateDescription
Gets or sets the template description. The template description.
####TargetTypes
Gets or sets the target types. The target types.
####TemplateParameters
Gets or sets the template parameters. The template parameters.
####Notifications
Gets or sets the notifications. The notifications.
####Frequency
Gets or sets the frequency. The frequency.
####DefaultRequiredConditionDuration
Gets or sets the default duration of the required condition. The default duration of the required condition.
####DefaultRenotificationPeriod
Gets or sets the default renotification period. The default renotification period.
####RuleAction
The action associated with the group
####
Textual identifier The identifier.
####
Current culture. Defaults to en-US. The current culture.
####
Gets the name of the parameter in the current culture The name.
####
Gets the description of the parameter in the current culture The description.
####
Gets or sets the type of the value. The type of the value.
####
If ValueType is 6, Enum, this contains the entities describing the enum values The enum elements.
####
Gets or sets the units. The units.
####
String encoding of the default value The default value.
###Methods


####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the class.
> #####Parameters
> **culture:** The culture.

> **sourceTemplate:** The source template.


####Constructor
Initializes a new instance of the class.
> #####Parameters
> **cultureInfo:** The culture information.

> **monitorModelRuleTemplateParameter:** The monitor model rule template parameter.


##Monitor.Notifications.PowerShell.MonitorRuleTemplateParameter
            
Represents a rule template parameter
        
###Properties

####Id
Textual identifier The identifier.
####CultureName
Current culture. Defaults to en-US. The current culture.
####Name
Gets the name of the parameter in the current culture The name.
####Description
Gets the description of the parameter in the current culture The description.
####ValueType
Gets or sets the type of the value. The type of the value.
####EnumElements
If ValueType is 6, Enum, this contains the entities describing the enum values The enum elements.
####Units
Gets or sets the units. The units.
####DefaultValue
String encoding of the default value The default value.
###Methods


####Constructor
Initializes a new instance of the class.
> #####Parameters
> **cultureInfo:** The culture information.

> **monitorModelRuleTemplateParameter:** The monitor model rule template parameter.


##Monitor.Notifications.Pnaa.MonitorNotificationRuleTemplateParameterEnumElement
            
Descriptor of an enum element
        
###Properties

####Id
Textual identifier The identifier.
####CultureName
Current culture. Defaults to en-US. The current culture.
####Name
Gets the name of the element in the current culture The name.
####Description
Gets the description of the element in the current culture The description.
####ValueType
Type of value this element represents. Same enum as above. The type of the value.
####Value
Value of the entity. Must be parseable as type ValueType The value.
###Methods


####Constructor
Initializes a new instance of the class.
> #####Parameters
> **culture:** The culture.

> **source:** The source.


##Monitor.Notifications.Pnaa.MonitorNotificationSourceDefinition
            

        
###Properties

####Id
Gets or sets the identifier. The identifier.
####Reference
Gets or sets the reference. The reference.
####Parameters
Gets or sets the parameters. The parameters.
###Methods


####Constructor
Initializes a new instance of the class.
> #####Parameters
> **notificationSourceDefinition:** The notification condition definition.


##Monitor.Notifications.Pnaa.MonitorModelRuleTemplate
            
Represents a rule template
        
###Properties

####Id
Gets or sets the identifier. The identifier.
####CurrentCulture
Gets or sets the current culture. The current culture.
####TemplateName
Gets or sets the name of the template. The name of the template.
####TemplateDescription
Gets or sets the template description. The template description.
####TargetTypes
Gets or sets the target types. The target types.
####TemplateParameters
Gets or sets the template parameters. The template parameters.
####Notifications
Gets or sets the notifications. The notifications.
####Frequency
Gets or sets the frequency. The frequency.
####DefaultRequiredConditionDuration
Gets or sets the default duration of the required condition. The default duration of the required condition.
####DefaultRenotificationPeriod
Gets or sets the default renotification period. The default renotification period.
####
Textual identifier The identifier.
####
Current culture. Defaults to en-US. The current culture.
####
Gets the name of the parameter in the current culture The name.
####
Gets the description of the parameter in the current culture The description.
####
Gets or sets the type of the value. The type of the value.
####
If ValueType is 6, Enum, this contains the entities describing the enum values The enum elements.
####
Gets or sets the units. The units.
####
String encoding of the default value The default value.
###Methods


####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the class.
#####Parameters
> **id:** The identifier.

> **localizedNames:** The localized names.

> **localizedDescriptions:** The localized descriptions.

> **frequency:** 

> **reannouncementPeriod:** 

> **notifications:** The notifications.

> **targetTypes:** The target types.

> **parameters:** List of parameters to the rule template


####GetTemplateName(System.Globalization.CultureInfo)
Gets the name of the template.
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Template name in cultureName
> #####Exceptions
> **System.NotImplementedException:** 


####GetTemplateDescription(System.Globalization.CultureInfo)
Gets the template description.
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Template description in cultureName
> #####Exceptions
> **System.NotImplementedException:** 


####Constructor
Initializes a new instance of the class.
> #####Parameters
> **id:** The identifier.

> **localizedNameStrings:** The localized name strings.

> **localizedDescriptionStrings:** The localized description strings.

> **valueType:** Type of the value.

> **units:** The units.

> **enumElements:** The enum elements.

> **defaultValue:** Default Value


####
Gets the name of the parameter in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Name in culture cultureName

####
Gets the description of the parameter in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Description in culture cultureName

####
Gets the value converted to type T
> #####Return value
> The represented value as type T

####
Gets the units.
> #####Parameters
> **cultureInfo:** The culture information.

> #####Return value
> 

##Monitor.Notifications.Pnaa.MonitorModelRuleTemplateParameter
            
Represents a rule template parameter
        
###Properties

####Id
Textual identifier The identifier.
####CurrentCulture
Current culture. Defaults to en-US. The current culture.
####Name
Gets the name of the parameter in the current culture The name.
####Description
Gets the description of the parameter in the current culture The description.
####ValueType
Gets or sets the type of the value. The type of the value.
####EnumElements
If ValueType is 6, Enum, this contains the entities describing the enum values The enum elements.
####Units
Gets or sets the units. The units.
####DefaultValue
String encoding of the default value The default value.
###Methods


####Constructor
Initializes a new instance of the class.
> #####Parameters
> **id:** The identifier.

> **localizedNameStrings:** The localized name strings.

> **localizedDescriptionStrings:** The localized description strings.

> **valueType:** Type of the value.

> **units:** The units.

> **enumElements:** The enum elements.

> **defaultValue:** Default Value


####GetName(System.Globalization.CultureInfo)
Gets the name of the parameter in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Name in culture cultureName

####GetDescription(System.Globalization.CultureInfo)
Gets the description of the parameter in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Description in culture cultureName

####GetValueAs``1
Gets the value converted to type T
> #####Return value
> The represented value as type T

####GetUnits(System.Globalization.CultureInfo)
Gets the units.
> #####Parameters
> **cultureInfo:** The culture information.

> #####Return value
> 

##Monitor.Notifications.Pnaa.NotificationRuleTemplateParameterEnumElement
            
Descriptor of an enum element
        
###Properties

####Id
Textual identifier The identifier.
####CurrentCulture
Current culture. Defaults to en-US. The current culture.
####Name
Gets the name of the element in the current culture The name.
####Description
Gets the description of the element in the current culture The description.
####ValueType
Type of value this element represents. Same enum as above. The type of the value.
####Value
Value of the entity. Must be parseable as type ValueType The value.
###Methods


####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the class.
> #####Parameters
> **id:** The identifier.

> **name:** The name.

> **description:** The description.

> **type:** The type.

> **value:** The value.


####GetName(System.Globalization.CultureInfo)
Gets the name of the element in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Name text in culture cultureName

####GetDescription(System.Globalization.CultureInfo)
Gets the description of the element in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Description text in culture cultureName

##Monitor.Notifications.Interfaces.INotificationSourceDefinition
            
Represents a condition
        
###Properties

####Id
Gets or sets the identifier. The identifier.
####Reference
Gets or sets the reference. The reference.
####Parameters
Gets or sets the parameters. The parameters.

##Monitor.Notifications.Interfaces.INotificationConditionDefinition
            
Represents a condition
        
###Properties

####Id
Gets or sets the identifier. The identifier.
####Reference
Gets or sets the reference. The reference.
####Parameters
Gets or sets the parameters. The parameters.
####Operation
Gets or sets the operation The operation.
####Source
Gets or sets the source. The source.

##Monitor.Notifications.Interfaces.ConditionTargetType
            
What kind of item is targeted
        
###Fields

####Unknown
The unknown
####Site
The site
####Controller
The controller
####DesktopGroup
The delivery group
####Catalog
The catalog
####RdsWorker
The RDS worker
####Vdi
The vdi
####User
User

##Monitor.Notifications.Interfaces.INotificationDefinition
            

        
###Properties

####Priority
An inverted priority specification where 0 is highest and Int.Max()-1 is the lowest The priority.
####Condition
The condition associated with this notification The condition.

##Monitor.Notifications.Interfaces.IInstantiatedRuleProvider
            
Provides access to active rules
        
###Properties

####RuleTemplateProvider
Gets or sets the rule template provider. The rule template provider.
####InstantiatedRules
Collection<> of configured rules The instantiated rules.
###Methods


####CompleteInitialization
Allows a concrete implmentation to finish initializing itself after unity setup

####Refresh
Update the internal view of the data if necessary

####BroadcastInstantiatedRulesAdded(System.Collections.Generic.List{System.Int64})
Called when instantiated rule added.

####BroadcastInstantiatedRulesModified(System.Collections.Generic.List{System.Int64})
Called when instantiated rule modified.

####BroadcastInstantiatedRulesRemoved(System.Collections.Generic.List{System.Int64})
Called when instantiated rule removed.

##Monitor.Notifications.Interfaces.IRuleTemplate
            
Represents a rule template
        
###Properties

####Id
Human readable identifier The identifier.
####CurrentCulture
Defaults to CultureInfo.CurrentCulture The current culture.
####TemplateName
Gets the name of the rule in the current culture The name of the template.
####TemplateDescription
Gets the description of the rule in the current culture The template description.
####TargetTypes
A list of the targets this rule template can target The target types.
####TemplateParameters
Collection>< of the parameters applied to this template, indexed by textual id The template parameters.
####Notifications
List of notifications contained in this rule. The notifications.
####Frequency
The length of time between queries and evaluations for this type of notification. This is treated as a hint by the system and may not be respected in v1. The frequency.
####DefaultRequiredConditionDuration
Length of time the condition must persist to be signaled (Default; can be overridden by rule instance) The default duration of the required condition.
####DefaultRenotificationPeriod
Length of time the condition must persist AFTER it is signaled before it is signaled again (Default; can be overridden by rule instance) The default renotification period.
####
Textual identifier The identifier.
####
Current culture. Defaults to en-US. The current culture.
####
Gets the name of the parameter in the current culture The name.
####
Gets the description of the parameter in the current culture The description.
####
Gets or sets the type of the value. The type of the value.
####
If ValueType is 6, Enum, this contains the entities describing the enum values The enum elements.
####
Gets or sets the default value. The default value.
####
Gets or sets the units. The units.
####
Textual identifier The identifier.
####
Current culture. Defaults to en-US. The current culture.
####
Gets the name of the element in the current culture The name.
####
Gets the description of the element in the current culture The description.
####
Type of value this element represents. Same enum as above. The type of the value.
####
Value of the entity. Must be parseable as type ValueType The value.
####
Collection<> of rules provided by this provider The templates.
###Methods


####GetTemplateName(System.Globalization.CultureInfo)
Returns the name of the template in the specified culture, or en-US if the current culture is not available.
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Gets the template name in culture cultureName

####GetTemplateDescription(System.Globalization.CultureInfo)
Returns the description of the template in the specified culture, or en-US if the current culture is not available.
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Gets the template name in culture cultureName

####
Gets the name of the parameter in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Template name in cultureName

####
Gets the description of the parameter in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Template description in cultureName

####
Gets the units.
> #####Parameters
> **cultureInfo:** The culture information.

> #####Return value
> 

####
Gets the name of the element in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> 

####
Gets the description of the element in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> 

####
Allows a concrete implmentation to finish initializing itself after unity setup

####
Returns a rule template with all the includes resolved into objects.
> #####Parameters
> **id:** The identifier.

> #####Return value
> 

##Monitor.Notifications.Interfaces.IRuleTemplateParameter
            
Represents a template parameter
        
###Properties

####Id
Textual identifier The identifier.
####CurrentCulture
Current culture. Defaults to en-US. The current culture.
####Name
Gets the name of the parameter in the current culture The name.
####Description
Gets the description of the parameter in the current culture The description.
####ValueType
Gets or sets the type of the value. The type of the value.
####EnumElements
If ValueType is 6, Enum, this contains the entities describing the enum values The enum elements.
####DefaultValue
Gets or sets the default value. The default value.
####Units
Gets or sets the units. The units.
####
Textual identifier The identifier.
####
Current culture. Defaults to en-US. The current culture.
####
Gets the name of the element in the current culture The name.
####
Gets the description of the element in the current culture The description.
####
Type of value this element represents. Same enum as above. The type of the value.
####
Value of the entity. Must be parseable as type ValueType The value.
###Methods


####GetName(System.Globalization.CultureInfo)
Gets the name of the parameter in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Template name in cultureName

####GetDescription(System.Globalization.CultureInfo)
Gets the description of the parameter in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> Template description in cultureName

####GetUnits(System.Globalization.CultureInfo)
Gets the units.
> #####Parameters
> **cultureInfo:** The culture information.

> #####Return value
> 

####
Gets the name of the element in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> 

####
Gets the description of the element in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> 

##Monitor.Notifications.Interfaces.IRuleTemplateParameterEnumElement
            

        
###Properties

####Id
Textual identifier The identifier.
####CurrentCulture
Current culture. Defaults to en-US. The current culture.
####Name
Gets the name of the element in the current culture The name.
####Description
Gets the description of the element in the current culture The description.
####ValueType
Type of value this element represents. Same enum as above. The type of the value.
####Value
Value of the entity. Must be parseable as type ValueType The value.
###Methods


####GetName(System.Globalization.CultureInfo)
Gets the name of the element in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> 

####GetDescription(System.Globalization.CultureInfo)
Gets the description of the element in the specified culture
> #####Parameters
> **cultureName:** Name of the culture.

> #####Return value
> 

##Monitor.Notifications.Interfaces.IRuleTemplateProvider
            

        
###Properties

####RuleTemplates
Collection<> of rules provided by this provider The templates.
###Methods


####CompleteInitialization
Allows a concrete implmentation to finish initializing itself after unity setup

####GetRuleTemplate(System.String)
Returns a rule template with all the includes resolved into objects.
> #####Parameters
> **id:** The identifier.

> #####Return value
> 

##Monitor.Notifications.Interfaces.RuleTemplateParameterValueType
            
Type of a rule template
        
###Fields

####Unknown
Unknown. For convention's sake. Should never occur.
####Int32

####UInt32

####Int64

####UInt64

####Float

####Double

####String

####Uuid

####Date
The date
####TimeSpan
The time span
####Enum
The enum