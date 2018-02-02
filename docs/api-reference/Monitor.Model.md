#Citrix.Monitor.Model


##Monitor.Model.TableInfoAttribute
            

        
###Properties

####Name


##Monitor.Model.Enums.ApplicationErrorSortBy
            
ApplicationErrorSortBy
        
###Fields

####Unknown
Unknown value for sort field
####Timestamp
Time at which error occurred

##Monitor.Model.Enums.ApplicationFaultSortBy
            
ApplicationFaultSortBy
        
###Fields

####Unknown
Unknown value for sort field
####Timestamp
Time at which fault occurred

##Monitor.Model.Enums.ApplicationUsageSortBy
            
DesktopUsageSortBy
        
###Fields

####Unknown
Unknown
####ApplicationName
ApplicationName
####PeakConcurrentApplicationInstances
PeakConcurrentApplicationInstances.
####TotalApplicationInstances
TotalApplicationInstances
####TotalApplicationLaunches
TotalApplicationLaunches
####ApplicationUsageDurationInHours
ApplicationUsageDurationInHours
####DistinctUsers
DistinctUsers
####ApplicationFolder
ApplicationFolder

##Monitor.Model.Enums.ApplicationInstanceSortBy
            
ResourceUsageSortBy
        
###Fields

####Unknown
Unknown
####PublishedName
PublishedName
####AssociatedUserName
AssociatedUserName
####MachineName
MachineName
####SessionState
SessionState
####SessionIdleTime
Session idle time since

##Monitor.Model.Enums.LogOnDetailsSortBy
            
DesktopUsageSortBy
        
###Fields

####Unknown
Unknown
####UserName
UserName
####DeliveryGroupName
DeliveryGroupName.
####MachineName
MachineName
####LogOnDate
LogOnDate
####Brokering
Brokering
####VMStart
VMStart
####HdxConnection
HdxConnection
####Authentication
Authentication
####Gpos
Gpos
####LogOnScripts
LogOnScripts
####ProfileLoad
ProfileLoad
####InteractiveSessions
InteractiveSessions
####TotalLogOnDuration
TotalLogOnDuration

##Monitor.Model.Enums.NotificationGroupState
            
What state is the notification group in?
        
###Fields

####Enabled
Default value - entity is active
####Disabled
Object was disabled
####Deleted
Object was deleted

##Monitor.Model.Enums.NotificationHistorySortBy
            
NotificationHistorySortBy enum
        
###Fields

####Unknown
unknown
####Date
Time
####Severity
Severity

##Monitor.Model.Enums.NotificationSummarySortBy
            
NotificationSummarySortBy
        
###Fields

####Unknown
Unknown
####Date
Date
####NotificationId
NotificationId
####NotificationState
NotificationState
####PolicyName
PolicyName
####PolicyId
PolicyId
####Scope
Scope
####SourceId
SourceId
####SourceName
SourceName
####SourceType
SourceType
####Category
Category

##Monitor.Model.Enums.NotificationSummaryState
            
Notification summary state
        
###Fields

####Unknown
Unknown.
####Warning
Warning state
####Critical
Critical state
####Healthy
Healthy state
####Dismissed
Dismissed state

##Monitor.Model.Enums.ProcessUsageSortBy
            
ProcessUsageSortBy
        
###Fields

####Unknown
Unknown
####ProcessName
MachineName
####AverageProcessorLoad
AverageProcessorLoad
####ProcessorLoadPeak
ProcessorLoadPeak
####AverageMemoryUtilization
AverageMemoryUtilization
####MemoryUtilizationPeak
MemoryUtilizationPeak

##Monitor.Model.Enums.ResourceUsageSortBy
            
ResourceUsageSortBy
        
###Fields

####Unknown
Unknown
####MachineName
MachineName
####TotalSessionCount
TotalSessionCount.
####AverageProcessorLoad
AverageProcessorLoad
####ProcessorLoadPeak
ProcessorLoadPeak
####AverageMemoryUtilization
AverageMemoryUtilization
####MemoryUtilizationPeak
MemoryUtilizationPeak

##Monitor.Model.Enums.NotificationLifecycle
            
Is it Dismissed or Active?
        
###Fields

####Unknown
Unknown.
####NotificationActive
Notification is not dismissed
####NotificationDismissed
Notification is dismissed
####NotificationComplete
No longer active

##Monitor.Model.Enums.ApplicationType
            
Set of application type values denoting how an application is hosted
        
###Fields

####HostedOnDesktop
The application is hosted from a desktop.
####InstalledOnClient
The application is installed on a client.

##Monitor.Model.Enums.DeliveryType
            
Specifies whether desktops, applications, or both, can be delivered from machines contained within the new desktop group. Desktop groups with a DesktopKind of Private cannot be used to deliver both desktops and applications. Defaults to DesktopsOnly if not specified.
        
###Fields

####DesktopsOnly
Only desktops are published.
####AppsOnly
Only applications are published.
####DesktopsAndApps
Both desktops and applications are published.

##Monitor.Model.Enums.DesktopType
            
Specifies whether desktops, applications, or both, can be delivered from machines contained within the new desktop group. Desktop groups with a DesktopKind of Private cannot be used to deliver both desktops and applications. Defaults to DesktopsOnly if not specified.
        
###Fields

####None
None
####Vdi
VM Hosted Desktop .
####RemotePc
UnManaged desktop RemotePC.
####Rds
VM Hosted RDS
####Unknown
unknown type

##Monitor.Model.Enums.DesktopUsageSortBy
            
DesktopUsageSortBy
        
###Fields

####Unknown
Unknown
####DeliveryGroupName
DeliveryGroupName
####MachineName
MachineName.
####UserName
UserName
####PeakConcurrentDesktopInstances
PeakConcurrentDesktopInstances
####TotalDesktopInstances
TotalDesktopInstances
####TotalDesktopLaunches
TotalDesktopLaunches
####DesktopUsageDurationInHours
DesktopUsageDurationInHours
####AverageDesktopUsageInHours
AverageDesktopUsageInHours
####DistinctUsers
DistinctUsers.

##Monitor.Model.Enums.HotfixChangeType
            
Enum to determine whether a hotfix was added or removed.
        
###Fields

####Add
Added
####Remove
Removed

##Monitor.Model.Enums.MachineRole
            
Enum to determine where machine is VDA or DDC
        
###Fields

####Vda
Vda machine
####Ddc
Ddc machine
####Both
Machine acting as VDA and DDC

##Monitor.Model.Enums.NotificationRulePriorityType
            
datatype of the NotificationRulePriorityType
        
###Fields

####Alarm

####Alert


##Monitor.Model.Enums.SessionDetailsSortBy
            
SessionDetailsSortBy enum
        
###Fields

####Unknown
Unknown
####UserName
UserName
####DeliveryGroupName
DeliveryGroupName.
####MachineName
MachineName
####SessionStart
Session StartDate
####SessionEnd
Session EndDate

##Monitor.Model.Enums.LogOnStep
            
Defines the steps in the logon process.
        
###Fields

####Total
Total
####Brokering
The time taken to complete the process of brokering the session.
####VMStart
In case the session required a machine to be started, the time taken to start the VM.
####Hdx
The time taken to complete the steps required in setting up the HDX connection from the client to the VM.
####Authentication
The time taken to complete authentication to the remote session.
####Gpos
In case any Group Policy settings have been enabled on the machines, the time taken for the GPOs to be applied.
####LogOnScripts
In case logon scripts are configured for the session, the time taken for the logon scripts to be executed.
####ProfileLoad
In case profile settings are configured for the user or the machine, the time taken for the profile to be loaded.
####Interactive
The time taken to handoff keyboard and mouse control to the user.

##Monitor.Model.Enums.NotificationRuleActionType
            
Denotes how the the machines in the catalog are allocated to a user.
        
###Fields

####Unknown
Unknown.
####Email


##Monitor.Model.Enums.NotificationRuleParameterType
            
datatype of the NotificationRuleParameter
        
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

##Monitor.Model.Enums.NotificationRuleTargetType
            
Denotes how the the machines in the catalog are allocated to a user.
        
###Fields

####Unknown
Unknown. When the Broker does not send an allocation type.
####Site

####Controller

####DesktopGroup

####Catalog

####RdsWorker

####Vdi

####User


##Monitor.Model.Enums.NotificationState
            
What state is the notification in?
        
###Fields

####Unknown
Unknown.
####NotificationBegan
Notification Began
####NotificationPending
Notification Pending
####NotificationTriggered
Notification Triggered
####NotificationAbandoned
Notification Abandoned
####NotificationPreempted
Notification Preempted
####NotificationCompleted
Notification Completed

##Monitor.Model.Enums.SessionType
            
Indicates if the session is running an Application or Desktop.
        
###Fields

####Desktop
Desktop session
####Application
Application session

##Monitor.Model.Enums.SortOrderType
            
SortOrderType
        
###Fields

####Unknown
Unknown
####Asc
Sort by ascending
####Desc
Sort by descending

##Monitor.Model.Enums.TaskResult
            
Enum for identifying the result of a scheduled database task
        
###Fields

####Unknown
Unknown result
####Success
Successfully run task
####Failure
Task failed
####Skipped
Task skipped without error

##Monitor.Model.Enums.DataManagementTask
            
Enum for identifying a scheduled database task
        
###Fields

####Unknown
Unknown task
####ConsolidateSessionActivity
Consolidate Session Activity
####ConsolidateLoadIndexes
Conslidate Load Indexes
####ConsolidateFailureLogs
Consolidate Failure Logs (connection and machine)
####GroomSessions
Groom ended sessions according to settings
####GroomLoadIndexes
Groom load indexes according to settings
####GroomSummaries
Groom summaries (minute, hourly, daily) - FailureLogSummary, SessionActivitySummary, LoadIndexSummary
####ReapMachines
Reap unresolved machines
####ReapSessions
Reap unresolved sessions
####ReapCatalogs
Reap unresolved catalogs
####ReapDesktopGroups
Reap unresolved desktop groups
####ReapHypervisors
Reap unresolved Hypervisors
####GroomFailureLogs
Groom FailureLog
####GroomDeleted
Groom LifecycleState = Deleted items (Machines, DesktopGroups, Hypervisors, Catalogs)
####GroomTaskLog
Groom TaskLog table, used in logging all data management jobs
####GroomMachineHotfixLog
Groom machine-hotfix history, stores the history all all hotfixes applied on a machine
####ConsolidateMachineSessionCount
Consolidate Machine Session counts
####GroomApplicationInstances
Groom application instance, stores the history of instances of applications started/ stopped
####ConsolidateApplicationActivity
Consolidate application usage activity
####GroomDesktopUsageData
Groom desktop usage, stores the history of instances of desktop sessions started/ stopped
####ConsolidateDesktopUsageActivity
Consolidate desktop usage activity
####GroomNotificationLog
Groom notification log table, stores the history of notification alarm/alerts that were fired off
####ConsolidateResourceUsageActivity
Consolidate resource usage activity
####ConsolidateProcessUsageActivity
Consolidate process usage activity
####GroomResourceUtilizationData
Groom Resource Utilization raw data, removes minute level data of resource usage
####GroomResourceUtilizationSummaryData
Groom Resource Utilization summary data, removes consolidated 10 minutes, 1 hour and 1 day level data of resource usage
####GroomProcessUtilizationData
Groom Process Utilization raw data, removes minute level data
####GroomProcessUtilizationMinuteData
Groom Process Utilization Minute data, removes consolidated minutes level data
####GroomSessionMetricsData
Groom SessionMetrics raw data
####ReapApplications
Reap unresolved applications
####GroomProcessUtilizationHourData
Groom Process Utilization Hour data, removes consolidated hours level data
####GroomProcessUtilizationDayData
Groom Process Utilization Day data, removes consolidated days level data
####ConsolidateMachineMetric
Consolidate Disk Utilization data
####GroomMachineMetricData
Groom Machine Metric Data, removes Raw Data
####GroomMachineMetricDaySummaryData
Groom Machine Metric Data, removes consolidated days level data
####GroomApplicationFaults
Groom Application Faults Data
####GroomApplicationErrors
Groom Application Errors Data

##Monitor.Model.Enums.TaskCategory
            
Enum for identifying the cateogry of a scheduled database task
        
###Fields

####Unknown
Unknown category
####Consolidation
Data Consolidation
####Reaping
Reaping of unresolved data
####Grooming
Grooming away old/deleted data

##Monitor.Model.Enums.AllocationType
            
Denotes how the the machines in the catalog are allocated to a user.
        
###Fields

####Unknown
Unknown. When the Broker does not send an allocation type.
####Static
Machines get assigned to a user either by the admin or on first use. This relationship is static and changes only if an admin explicitly changes the assignments.
####Random
Machines are allocated to users randomly from a pool of available machines.
####Permanent
Equivalent to 'Static'

##Monitor.Model.Enums.ConnectionFailureType
            
Type of failures for Connections
        
###Fields

####None
None
####ClientConnectionFailure
Session failed to start
####MachineFailure
Machine Failure
####NoCapacityAvailable
No available capacity to start/ reconnect to a session
####NoLicensesAvailable
No Licenses Available
####Configuration
Configuration failure

##Monitor.Model.Enums.ConnectionState
            
Enum for session connections status
        
###Fields

####Unknown
Default value - unknown
####Connected
Actively connected to desktop
####Disconnected
Disconnected from desktop, but session still exists
####Terminated
Session has been terminated
####PreparingSession
Session is in the preparing state
####Active
Session is active
####Reconnecting
User is reconnecting to the session
####NonBrokeredSession
Session is non-brokered
####Other
Connection state is reported as Other
####Pending
Connection state is pending

##Monitor.Model.Enums.PersistentUserChangesType
            
Describes if and how user changes are persisted
        
###Fields

####Unknown
Unknown
####Discard
User changes are discarded.
####OnLocal
User changes are persisted locally.
####OnPvd
User changes are persisted on the Pvd.

##Monitor.Model.Enums.ProvisioningType
            
Describes how the machine was provisioned
        
###Fields

####Unknown
Unknown
####MCS
Machine provisioned by Machine Creation Services (machine must be a VM).
####PVS
Machine provisioned by Provisioning Services (may be physical, blade, VM,...).
####Manual
No automated provisioning.

##Monitor.Model.Enums.FailureCategory
            
Category for failure types
        
###Fields

####Unknown
Default value - unknown
####Connection
Connection failure category
####Machine
Machine failure category

##Monitor.Model.Enums.RegistrationState
            
Indicates the registration state of the machine.
        
###Fields

####Unknown
Unknown
####Registered
Machine is currently registered.
####Unregistered
Machine has been unregistered.

##Monitor.Model.Enums.CatalogType
            
Type of Catalog Broker name: CatalogKind Desktop Director name: Machine Type The type of machines the catalog will contain.
        
###Fields

####ThinCloned
A thin-cloned catalog is used for original golden VM images that are cloned when they are assigned to a VM, and users' changes to the VM image are retained after the VM is restarted.
####SingleImage
A single-image catalog is used when multiple machines provisioned with Provisioning Services for VMs all share a single golden VM image when they run and, when restarted, they revert to the original VM image state.
####PowerManaged
This catalog kind is for managed machines that are manually provisioned by administrators. All machines in this type of catalog are managed, and so must be associated with a hypervisor connection.
####Unmanaged
This catalog kind is for unmanaged machines, so there is no associated hypervisor connection.
####Pvs
This catalog kind is for managed machines that are provisioned using Provisioning Services. All machines in this type of catalog are managed, and so must be associated with a hypervisor connection. Only shared desktops are suitable for this catalog kind.
####Pvd
A personal vDisk catalog is similar to a single-image catalog, but it also uses personal vDisk technology.
####PvsPvd
A Provisioning Services-personal vDisk (PvsPvd) catalog is similar to a Provisioning Services catalog, but it also uses personal vDisk technology.

##Monitor.Model.Enums.DesktopKind
            
The kind of desktops within a delivery group.
        
###Fields

####Private
Private
####Shared
Shared

##Monitor.Model.Enums.LifecycleState
            
Enum tracking state of XenDesktop site objects
        
###Fields

####Active
Default value - entity is active
####Deleted
Object was deleted
####RequiresResolution
Object was created, but values are missing, so a background process should poll to update missing values
####Stub
Stub object - for example, a Machine or Session that didn't really exist but is created by internal processing logic to preserve data relationships

##Monitor.Model.Enums.LogOnBreakdownType
            
Enum for logon breakdown api calls
        
###Fields

####None
Default value of none
####UsersLastSession
User's last session information
####UsersSessionAverage
Average across the user's sessions
####DesktopGroupAverage
Average for the desktop group

##Monitor.Model.MachineMetricBulkInsertModel
            
Represents a machine metrics statistics of a particular machine.
        
###Properties

####CollectedDate
Date this object was created
####Iops
Iops on the machine
####Latency
Latency on the machine
####MachineId
Guid of machine this MachineMetric record is associated with
###Methods


####Constructor
Initializes a new instance of the MachineMetricBulkInsertModel class.

##Monitor.Model.MachineMetric
            

        
###Properties

####
Date this object was created
####
Iops on the machine
####
Latency on the machine
####
Guid of machine this MachineMetric record is associated with
####Machine
The machine this MachineMetric record is associated with
####
Beginning timeslot (to the minute) this Summary date represent
####
Machine unique id
####
Actual Machine object
####
Average IOPS for given SummaryDate Eg: Lets say iops for this machine available at times 10:00,11:00,...,21:00 Lets say summary is calculated for every 1 DAY(i.e., granularity) SummaryDate will be DAY x 00:00 and Average will be calculated for above records
####
Peak IOPS given SummaryDate Eg: Lets say iops for this machine available at times 10:00,11:00,...,21:00 Lets say summary is calculated for every 1 DAY(i.e., granularity) SummaryDate will be DAY x 00:00 and Peak will be calculated for above records
####
Average Latency on the machine for given SummaryDate
###Methods


####Constructor
Initializes a new instance of the MachineMetricBulkInsertModel class.

####Constructor
Initializes a new instance of the MachineMetricDaySummary class.

##Monitor.Model.MachineMetricDaySummary
            
Summary table for MachineMetric
        
###Properties

####SummaryDate
Beginning timeslot (to the minute) this Summary date represent
####MachineId
Machine unique id
####Machine
Actual Machine object
####AvgIops
Average IOPS for given SummaryDate Eg: Lets say iops for this machine available at times 10:00,11:00,...,21:00 Lets say summary is calculated for every 1 DAY(i.e., granularity) SummaryDate will be DAY x 00:00 and Average will be calculated for above records
####PeakIops
Peak IOPS given SummaryDate Eg: Lets say iops for this machine available at times 10:00,11:00,...,21:00 Lets say summary is calculated for every 1 DAY(i.e., granularity) SummaryDate will be DAY x 00:00 and Peak will be calculated for above records
####AvgLatency
Average Latency on the machine for given SummaryDate
###Methods


####Constructor
Initializes a new instance of the MachineMetricDaySummary class.

##Monitor.Model.ProcessInfoBulkInsertModel
            
Represents a process utilization statistics of a particular process on a machine.
        
###Properties

####ProcessKey

####ProcessId

####ProcessName

####ProcessCreationDate
Date this process was created
####ApplicationName

####MachineId
Guid of machine this ProcessInfo record is associated with
####SessionId

###Methods


####Constructor
Initializes a new instance of the ProcessInfoBulkInsertModel class.

##Monitor.Model.ProcessInfo
            

        
###Properties

####

####

####

####
Date this process was created
####

####
Guid of machine this ProcessInfo record is associated with
####

####Machine
The machine this ResourceUtilization record is associated with
####Session
The session this ResourceUtilization record is associated with
####ProcessUtilization
ProcessUtilization values associated with this process
####ProcessUtilizationMinuteSummary
ProcessUtilizationMinuteSummary values associated with this process
####ProcessUtilizationHourSummary
ProcessUtilizationHourSummary values associated with this process
####ProcessUtilizationDaySummary
ProcessUtilizationDaySummary values associated with this process
###Methods


####Constructor
Initializes a new instance of the ProcessInfoBulkInsertModel class.

##Monitor.Model.ProcessUtilizationBulkInsertModel
            
Represents a process utilization statistics of a particular process on a machine.
        
###Properties

####CollectedDate
Date this object was created
####PercentCpu

####PercentMemory

####ProcessKey

####MachineId
Machine unique id
###Methods


####Constructor
Initializes a new instance of the ProcessUtilizationBulkInsertModel class.

##Monitor.Model.ProcessUtilization
            

        
###Properties

####
Date this object was created
####

####

####

####
Machine unique id
####ProcessInfo
The machine this ProcessUtilization record is associated with
####Machine
Actual Machine object
####
Beginning timeslot (to the minute) this Summary date represent
####

####
The machine this ProcessUtilizationDaySummary record is associated with
####
Machine unique id
####
Actual Machine object
####
Average percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####
Peak percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####
Average of Memory used for given SummaryDate Eg: Lets say memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####
Peak of Memory used for given SummaryDate Eg: Lets say Memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####
Beginning timeslot (to the minute) this Summary date represent
####

####
The machine this ProcessUtilizationHourSummary record is associated with
####
Machine unique id
####
Actual Machine object
####
Average percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####
Peak percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####
Average of Memory used for given SummaryDate Eg: Lets say memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####
Peak of Memory used for given SummaryDate Eg: Lets say Memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####
Beginning timeslot (to the minute) this Summary date represent
####

####
The machine this ProcessUtilizationMinuteSummary record is associated with
####
Machine unique id
####
Actual Machine object
####
Average percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####
Peak percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####
Average of Memory used for given SummaryDate Eg: Lets say memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####
Peak of Memory used for given SummaryDate Eg: Lets say Memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
###Methods


####Constructor
Initializes a new instance of the ProcessUtilizationBulkInsertModel class.

####Constructor
Initializes a new instance of the ProcessUtilizationDaySummary class.

####Constructor
Initializes a new instance of the ProcessUtilizationHourSummary class.

####Constructor
Initializes a new instance of the ProcessUtilizationMinuteSummary class.

##Monitor.Model.ProcessUtilizationDaySummary
            
Day level Summary table for ProcessUtilization
        
###Properties

####SummaryDate
Beginning timeslot (to the minute) this Summary date represent
####ProcessKey

####ProcessInfo
The machine this ProcessUtilizationDaySummary record is associated with
####MachineId
Machine unique id
####Machine
Actual Machine object
####AvgPercentCpu
Average percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####PeakPercentCpu
Peak percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####AvgPercentMemory
Average of Memory used for given SummaryDate Eg: Lets say memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####PeakPercentMemory
Peak of Memory used for given SummaryDate Eg: Lets say Memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
###Methods


####Constructor
Initializes a new instance of the ProcessUtilizationDaySummary class.

##Monitor.Model.ProcessUtilizationHourSummary
            
Hour level Summary table for ProcessUtilization
        
###Properties

####SummaryDate
Beginning timeslot (to the minute) this Summary date represent
####ProcessKey

####ProcessInfo
The machine this ProcessUtilizationHourSummary record is associated with
####MachineId
Machine unique id
####Machine
Actual Machine object
####AvgPercentCpu
Average percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####PeakPercentCpu
Peak percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####AvgPercentMemory
Average of Memory used for given SummaryDate Eg: Lets say memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####PeakPercentMemory
Peak of Memory used for given SummaryDate Eg: Lets say Memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
###Methods


####Constructor
Initializes a new instance of the ProcessUtilizationHourSummary class.

##Monitor.Model.ProcessUtilizationMinuteSummary
            
Minute level Summary table for ProcessUtilization
        
###Properties

####SummaryDate
Beginning timeslot (to the minute) this Summary date represent
####ProcessKey

####ProcessInfo
The machine this ProcessUtilizationMinuteSummary record is associated with
####MachineId
Machine unique id
####Machine
Actual Machine object
####AvgPercentCpu
Average percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####PeakPercentCpu
Peak percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####AvgPercentMemory
Average of Memory used for given SummaryDate Eg: Lets say memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####PeakPercentMemory
Peak of Memory used for given SummaryDate Eg: Lets say Memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
###Methods


####Constructor
Initializes a new instance of the ProcessUtilizationMinuteSummary class.

##Monitor.Model.SessionMetricsBulkInsertModel
            
Represents a session metrics of a particular session for a machine.
        
###Properties

####Id
Autogenerated id for Session Metrics record
####CollectedDate
Date this object was collected from source
####IcaRttMS

####CreatedDate
Date this object was created in database
####ModifiedDate
Date this object was modified in database
####SessionId
Guid of machine this SessionMetrics record is associated with
###Methods


####Constructor
Initializes a new instance of the SessionMetricsBulkInsertModel class.

##Monitor.Model.SessionMetrics
            

        
###Properties

####
Autogenerated id for Session Metrics record
####
Date this object was collected from source
####

####
Date this object was created in database
####
Date this object was modified in database
####
Guid of machine this SessionMetrics record is associated with
####Session
The machine this ResourceUtilization record is associated with
###Methods


####Constructor
Initializes a new instance of the SessionMetricsBulkInsertModel class.

##Monitor.Model.ResourceUtilizationSummary
            
Summary table for ResourceUtilization
        
###Properties

####SummaryDate
Beginning timeslot (to the minute) this Summary date represent
####MachineId
Machine unique id
####Machine
Actual Machine object
####DesktopGroupId
Guid of DesktopGroup this ResourceUtilizationSummary record is associated with
####DesktopGroup
The DesktopGroup this ResourceUtilizationSummary record is associated with
####AvgPercentCpu
Average percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####PeakPercentCpu
Peak percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####AvgUsedMemory
Average of Memory used for given SummaryDate Eg: Lets say memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####PeakUsedMemory
Peak of Memory used for given SummaryDate Eg: Lets say Memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####AvgTotalMemory
Total Memory available with Machine
####TotalSessionCount
Total sessions running for given SummaryDate
####Granularity
Granularity of this summary item in minutes (how many minutes of data included in this time slot)
###Methods


####Constructor
Initializes a new instance of the ResourceUtilizationSummary class.

##Monitor.Model.Pnaa.NotificationRuleParameterChangeLog
            
NotificationRule instance
        
###Properties

####Id
Unique identifier for the NotificationRule
####ChangeTime
When the change happened.
####NotificationRule
Parent rule
####NotificationRuleId
Parent rule id
####NotificationRuleParameters
List of parameters for this NotificationRule
###Methods


####Constructor
Initializes a new instance of the NotificationRule class.

##Monitor.Model.Pnaa.NotificationEmailServerConfiguration
            
NotificationRule instance
        
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
####Site
Mail UserName
####EncryptedPassword
EncryptedPassword
###Methods


####Constructor
Initializes a new instance of the NotificationRule class.

##Monitor.Model.Pnaa.NotificationSnmpConfiguration
            
NotificationRule instance
        
###Properties

####Id
Unique identifier for the MonitorNotificationRule
####HostName
Server address
####Port
Server port
####Sender
SNMP UserName
####AuthPassword
Auth password
####PrivatePassword
Privacy password
####AuthPasswordProtocol
Auth Protocol used for encrypting
####PrivatePasswordProtocol
Privacy protocol used for encryption
####EngineId
Engine ID
####CommunityString
community string
####Protocol
snmp protocol
###Methods


####Constructor
Initializes a new instance of the NotificationRule class.

##Monitor.Model.Pnaa.NotificationTargetValue
            
NotificationRuleTargetValue instance
        
###Properties

####Id
Unique identifier for the NotificationRuleTargetValue
####Value
Value portion of NotificationRuleTargetValue value pair
####NotificationTargetId
NotificationRuleTarget object with which this value is associated explicitly included for PowerPivot functionality
####NotificationTarget
references the NotificationRuleTarget instance to which this value belongs NOTE: there will be "n" rows per NotificationRuleTarget record
###Methods


####Constructor
Initializes a new instance of the NotificationRuleTargetValue class.

##Monitor.Model.Pnaa.NotificationTarget
            
NotificationRule instance
        
###Properties

####
Unique identifier for the NotificationRuleTargetValue
####
Value portion of NotificationRuleTargetValue value pair
####
NotificationRuleTarget object with which this value is associated explicitly included for PowerPivot functionality
####
references the NotificationRuleTarget instance to which this value belongs NOTE: there will be "n" rows per NotificationRuleTarget record
####Id
Unique identifier for the NotificationRule
####NotificationRuleTargetType
TargetType A string representation of the text Id that references the template in the Rule Template XML file This is not a database foreign key
####NotificationId
foreign key identifier to the NotificationRule explicitly included for PowerPivot functionality
####Notification
navigation object reference to the NotificationRule
####NotificationTargetValues
List of target values for this NotificationRuleTarget
###Methods


####Constructor
Initializes a new instance of the NotificationRuleTargetValue class.

####Constructor
Initializes a new instance of the class.

##Monitor.Model.Pnaa.InstantiatedRuleChangeType
            
Kind of change represented
        
###Fields

####Unknown
The unknown
####Add
The add
####Modify
The modify
####Remove
The remove

##Monitor.Model.Pnaa.NotificationActionEmail
            

        
###Properties

####Id
Unique Action Id
####Action
Action to which this action email belongs
####EmailAddresses
List of email addresses to send to for this action
####ServerConfiguration
Server to send emails with
####CultureName
Culture name to identify language to send emails in

##Monitor.Model.Pnaa.NotificationEmailAddress
            

        
###Properties

####Id

####EmailAddress

####NotificationActionEmail

####NotificationActionEmailId


##Monitor.Model.Pnaa.LocalizedString
            
Contains a localized string and its identified culture
        
###Properties

####CultureName
Gets or sets the name of the culture. The name of the culture.
####LocalizedResource
Gets or sets the localized resource. The localized resource.
###Methods


####Constructor
Initializes a new instance of the class.
> #####Parameters
> **cultureName:** Name of the culture.

> **localizedResource:** The localized resource.


##Monitor.Model.Pnaa.Notification
            
NotificationRule instance
        
###Properties

####
Unique identifier for the NotificationRule
####
When the change happened.
####
Parent rule
####
Parent rule id
####
List of parameters for this NotificationRule
####
Unique identifier for the MonitorNotificationRule
####
Mail protocol
####
Server address
####
Server port
####
Sender id
####
Whether the server requires authentication
####
Mail UserName
####
Mail UserName
####
EncryptedPassword
####
Unique identifier for the MonitorNotificationRule
####
Server address
####
Server port
####
SNMP UserName
####
Auth password
####
Privacy password
####
Auth Protocol used for encrypting
####
Privacy protocol used for encryption
####
Engine ID
####
community string
####
snmp protocol
####
Unique identifier for the NotificationRuleTargetValue
####
Value portion of NotificationRuleTargetValue value pair
####
NotificationRuleTarget object with which this value is associated explicitly included for PowerPivot functionality
####
references the NotificationRuleTarget instance to which this value belongs NOTE: there will be "n" rows per NotificationRuleTarget record
####
Unique identifier for the NotificationRule
####
TargetType A string representation of the text Id that references the template in the Rule Template XML file This is not a database foreign key
####
foreign key identifier to the NotificationRule explicitly included for PowerPivot functionality
####
navigation object reference to the NotificationRule
####
List of target values for this NotificationRuleTarget
####
Unique Action Id
####
Action to which this action email belongs
####
List of email addresses to send to for this action
####
Server to send emails with
####
Culture name to identify language to send emails in
####

####

####

####

####Id
Unique identifier for the NotificationRule
####FirstTimeConditionTrue
first time in this cycle the condition for this rule was evaluated true
####FirstTimeNotificationTriggered
first time in this cycle the condition was true and the waiting period had expired
####LastReannouncementTime
last time this was reannounced
####LastTimeConditionTrue
last time this was reannounced
####LifecycleState
Lifecycle state for the Machine. Used internally for data management.
####NotificationRuleId
foreign key to the NotificationRule instance explicitly included for PowerPivot functionality
####NotificationRule
references the NotificationRule instance upon which this current notification is based
####NotificationTarget
Active target tracked in this rule notification
####NotificationTargetId
Active target tracked in this rule notification
####NotificationPriority
Priority of the notification being referenced
####NotificationLogs
List of historical notifications for this Notification
####
Unique identifier for the NotificationRule
####
state of this NotificationLog object
####
NotificationStateChangeDate
####
IsReannouncement - will be true if this is a triggered event and it has been previously noted
####
navigation object reference to the NotificationRule
####
foreign key identifier to the NotificationRule explicitly included for PowerPivot functionality
####
Priority of the notification being referenced
####
foreign key identifier to the Notification object explicitly included for PowerPivot functionality
####
references most current Notification instance that relates to this NotificationLog record
####
Active target tracked in this rule notification
####
Unique identifier for the NotificationRule
####
TODO: Should go. Not required.
####
Type of NotificationAction
####
List of NotificationRules that use this NotificationRuleAction
####
Unique identifier for the NotificationRule
####
Gets or sets a value indicating whether this is enabled. true if enabled; otherwise, false.
####
Gets or sets a value indicating whether the targets of this rule should be aggregated or evaluated individually.
####
Name of NotificationRule Desktop Director name: do we need this?
####
Description of NotificationRule
####
TemplateId A string representation of the text Id that references the template in the Rule Template XML file This is not a database foreign key
####
List of parameters for this NotificationRule
####
List of targets for this NotificationRule
####
List of actions for this NotificationRule
####
Optional group to which this belongs
####
Optional group to which this belongs
####
Not a database field
####
Unique identifier for the NotificationRule
####
Name of NotificationRule Desktop Director name: do we need this?
####
Description of NotificationRule
####
webhook URL for the NotificationRuleGroup
####
The boolean value to check if SNMP is enabled
####
State of the notification group
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
navigation object reference to the NotificationRule
####
Optional rule parameter change log
####
Optional rule parameter change log
####
Unique identifier for the NotificationRule
####
Name of NotificationRule Desktop Director name: do we need this?
####
TargetType A string representation of the text Id that references the template in the Rule Template XML file This is not a database foreign key
####
foreign key identifier to the NotificationRule explicitly included for PowerPivot functionality
####
navigation object reference to the NotificationRule
####
List of target values for this NotificationRuleTarget
####
Unique identifier for the NotificationRuleTargetValue
####
Value portion of NotificationRuleTargetValue value pair
####
NotificationRuleTarget object with which this value is associated explicitly included for PowerPivot functionality
####
references the NotificationRuleTarget instance to which this value belongs NOTE: there will be "n" rows per NotificationRuleTarget record
###Methods


####Constructor
Initializes a new instance of the NotificationRule class.

####Constructor
Initializes a new instance of the NotificationRule class.

####Constructor
Initializes a new instance of the NotificationRule class.

####Constructor
Initializes a new instance of the NotificationRuleTargetValue class.

####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the NotificationRule class.

####Constructor
Initializes a new instance of the NotificationRule class.

####Constructor
Initializes a new instance of the NotificationAction class.

####Constructor
Initializes a new instance of the NotificationRule class.

####Constructor
Initializes a new instance of the NotificationRuleGroup> class.

####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the NotificationRuleTargetValue class.

##Monitor.Model.Pnaa.NotificationLog
            
NotificationLog instance
        
###Properties

####Id
Unique identifier for the NotificationRule
####NotificationState
state of this NotificationLog object
####NotificationStateChangeDate
NotificationStateChangeDate
####IsReannouncement
IsReannouncement - will be true if this is a triggered event and it has been previously noted
####NotificationRule
navigation object reference to the NotificationRule
####NotificationRuleId
foreign key identifier to the NotificationRule explicitly included for PowerPivot functionality
####NotificationPriority
Priority of the notification being referenced
####NotificationId
foreign key identifier to the Notification object explicitly included for PowerPivot functionality
####Notification
references most current Notification instance that relates to this NotificationLog record
####NotificationTarget
Active target tracked in this rule notification
###Methods


####Constructor
Initializes a new instance of the NotificationRule class.

##Monitor.Model.Pnaa.NotificationRuleAction
            
NotificationRule instance
        
###Properties

####Id
Unique identifier for the NotificationRule
####Name
TODO: Should go. Not required.
####NotificationRuleActionType
Type of NotificationAction
####NotificationRules
List of NotificationRules that use this NotificationRuleAction
###Methods


####Constructor
Initializes a new instance of the NotificationAction class.

##Monitor.Model.Pnaa.NotificationRule
            
NotificationRule instance
        
###Properties

####
Unique identifier for the NotificationRule
####
When the change happened.
####
Parent rule
####
Parent rule id
####
List of parameters for this NotificationRule
####
Unique identifier for the NotificationRule
####
TODO: Should go. Not required.
####
Type of NotificationAction
####
List of NotificationRules that use this NotificationRuleAction
####Id
Unique identifier for the NotificationRule
####Enabled
Gets or sets a value indicating whether this is enabled. true if enabled; otherwise, false.
####IsAggregate
Gets or sets a value indicating whether the targets of this rule should be aggregated or evaluated individually.
####Name
Name of NotificationRule Desktop Director name: do we need this?
####Description
Description of NotificationRule
####NotificationTemplateId
TemplateId A string representation of the text Id that references the template in the Rule Template XML file This is not a database foreign key
####NotificationRuleParameters
List of parameters for this NotificationRule
####NotificationRuleTargets
List of targets for this NotificationRule
####NotificationRuleActions
List of actions for this NotificationRule
####NotificationRuleGroup
Optional group to which this belongs
####NotificationRuleGroupId
Optional group to which this belongs
####NextDueAt
Not a database field
####
Unique identifier for the NotificationRule
####
Name of NotificationRule Desktop Director name: do we need this?
####
Description of NotificationRule
####
webhook URL for the NotificationRuleGroup
####
The boolean value to check if SNMP is enabled
####
State of the notification group
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
navigation object reference to the NotificationRule
####
Optional rule parameter change log
####
Optional rule parameter change log
####
Unique identifier for the NotificationRule
####
Name of NotificationRule Desktop Director name: do we need this?
####
TargetType A string representation of the text Id that references the template in the Rule Template XML file This is not a database foreign key
####
foreign key identifier to the NotificationRule explicitly included for PowerPivot functionality
####
navigation object reference to the NotificationRule
####
List of target values for this NotificationRuleTarget
####
Unique identifier for the NotificationRuleTargetValue
####
Value portion of NotificationRuleTargetValue value pair
####
NotificationRuleTarget object with which this value is associated explicitly included for PowerPivot functionality
####
references the NotificationRuleTarget instance to which this value belongs NOTE: there will be "n" rows per NotificationRuleTarget record
###Methods


####Constructor
Initializes a new instance of the NotificationRule class.

####Constructor
Initializes a new instance of the NotificationAction class.

####Constructor
Initializes a new instance of the NotificationRule class.

####Constructor
Initializes a new instance of the NotificationRuleGroup> class.

####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the NotificationRuleTargetValue class.

##Monitor.Model.Pnaa.NotificationRuleGroup
            
NotificationRule instance
        
###Properties

####Id
Unique identifier for the NotificationRule
####Name
Name of NotificationRule Desktop Director name: do we need this?
####Description
Description of NotificationRule
####Webhook
webhook URL for the NotificationRuleGroup
####IsSnmpEnabled
The boolean value to check if SNMP is enabled
####NotificationGroupState
State of the notification group
####NotificationRules
List of rules in the group
###Methods


####Constructor
Initializes a new instance of the NotificationRuleGroup> class.

##Monitor.Model.Pnaa.NotificationRuleParameter
            
Catalog image
        
###Properties

####
Unique identifier for the NotificationRule
####
When the change happened.
####
Parent rule
####
Parent rule id
####
List of parameters for this NotificationRule
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
####NotificationRule
navigation object reference to the NotificationRule
####NotificationRuleParameterChangeLogId
Optional rule parameter change log
####NotificationRuleParameterChangeLog
Optional rule parameter change log
###Methods


####Constructor
Initializes a new instance of the NotificationRule class.

####Constructor
Initializes a new instance of the class.

##Monitor.Model.Pnaa.NotificationRuleTarget
            
NotificationRule instance
        
###Properties

####Id
Unique identifier for the NotificationRule
####Name
Name of NotificationRule Desktop Director name: do we need this?
####NotificationRuleTargetType
TargetType A string representation of the text Id that references the template in the Rule Template XML file This is not a database foreign key
####NotificationRuleId
foreign key identifier to the NotificationRule explicitly included for PowerPivot functionality
####NotificationRule
navigation object reference to the NotificationRule
####NotificationRuleTargetValues
List of target values for this NotificationRuleTarget
####
Unique identifier for the NotificationRuleTargetValue
####
Value portion of NotificationRuleTargetValue value pair
####
NotificationRuleTarget object with which this value is associated explicitly included for PowerPivot functionality
####
references the NotificationRuleTarget instance to which this value belongs NOTE: there will be "n" rows per NotificationRuleTarget record
###Methods


####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the NotificationRuleTargetValue class.

##Monitor.Model.Pnaa.NotificationRuleTargetValue
            
NotificationRuleTargetValue instance
        
###Properties

####Id
Unique identifier for the NotificationRuleTargetValue
####Value
Value portion of NotificationRuleTargetValue value pair
####NotificationRuleTargetId
NotificationRuleTarget object with which this value is associated explicitly included for PowerPivot functionality
####NotificationRuleTarget
references the NotificationRuleTarget instance to which this value belongs NOTE: there will be "n" rows per NotificationRuleTarget record
###Methods


####Constructor
Initializes a new instance of the NotificationRuleTargetValue class.

##Monitor.Model.Application
            
Represents a virtualized application running on a session.
        
###Properties

####Id
Unique identifier for the application
####Name
Unique administrative name of application
####PublishedName
The name published to the end user corresponding to the Broker SDK's "PublishedName" property
####ApplicationType
Type of the application, whether HostedOnDesktop or InstalledOnClient, corresponding to the ApplicationType enumeration.
####Enabled
Specifies whether or not this application can be launched.
####AdminFolder
Admin Folder
####LifecycleState
Lifecycle state for the Application user for internal tracking and deletion management.
####Path
Path of the application published on the VDA
####BrowserName
BrowserName associated with Application
####DesktopGroups
The Delivery groups this application is related to.
####ApplicationInstances
Set of historical instances of the application that have run or are running.
####
Unique identifier of the application error
####
Path of the application
####
Process Name
####
Unique identifier of the session
####
Application Version
####
Error Description
####
Date when the application error occurred
####
List of Applications running in the session
####
Guid of machine this Error record is associated with
####
Session this error is associated with
####
The machine this Error record is associated with
####
Unique identifier of the application fault
####
Path of the application
####
Process Name
####
Unique identifier of the session
####
Application Version
####
Fault Description
####
Date when the application fault occurred
####
List of Applications running in the session
####
Guid of machine this Fault record is associated with
####
Session this fault is associated with
####
The machine this Fault record is associated with
####
Unique identifier of the application instance
####
Guid of the application
####
Guid of the session this application instance was created on (See Session property).
####
Date when the application was started
####
Date when the application was terminated
####
Application associated this application instance
####
The session associated with the application
####
Unique identifier for ApplicationInstanceSummary
####
Beginning time (to the minute) that this summary data represents The summary date.
####
Guid of the application this instance summary corresponds to (see Application property)
####
The application this summary data represents The application
####
The Id of the Delivery Group this application instance is associated with.
####
The delivery group this application instance is associated with The desktop group.
####
Number of peak concurrent instances of the application for the time slot specified The count of peak concurrent instances.
####
Total application usage duration in milliseconds for all instances of this application for the time slot specified The total duration of the application usage.
####
Total number of application launch events in the time slot
####
Number of application instances at the start of the summary window (see SummaryDate) The starting count of application instances for this period.
####
Granularity of this summary item in minutes (how many minutes of data included in this time slot) The granularity.
###Methods


####Constructor
Initializes a new instance of the Application class.

####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the ApplicationInstanceSummary class.

##Monitor.Model.ApplicationErrorBulkInsertModel
            
Represents Application Error data
        
###Properties

####Id
Unique identifier of the application error
####FaultingApplicationPath
Path of the application
####ProcessName
Process Name
####SessionKey
Unique identifier of the session
####Version
Application Version
####Description
Error Description
####ErrorReportedDate
Date when the application error occurred
####BrowserNames
List of Applications running in the session
####MachineId
Guid of machine this Error record is associated with
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.ApplicationError
            
Record of an application error
        
###Properties

####
Unique identifier of the application error
####
Path of the application
####
Process Name
####
Unique identifier of the session
####
Application Version
####
Error Description
####
Date when the application error occurred
####
List of Applications running in the session
####
Guid of machine this Error record is associated with
####Session
Session this error is associated with
####Machine
The machine this Error record is associated with
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.ApplicationFaultBulkInsertModel
            
Represents Application Fault data
        
###Properties

####Id
Unique identifier of the application fault
####FaultingApplicationPath
Path of the application
####ProcessName
Process Name
####SessionKey
Unique identifier of the session
####Version
Application Version
####Description
Fault Description
####FaultReportedDate
Date when the application fault occurred
####BrowserNames
List of Applications running in the session
####MachineId
Guid of machine this Fault record is associated with
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.ApplicationFault
            
Record of an application fault
        
###Properties

####
Unique identifier of the application fault
####
Path of the application
####
Process Name
####
Unique identifier of the session
####
Application Version
####
Fault Description
####
Date when the application fault occurred
####
List of Applications running in the session
####
Guid of machine this Fault record is associated with
####Session
Session this fault is associated with
####Machine
The machine this Fault record is associated with
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.ApplicationInstance
            
Record of an instance of a running application
        
###Properties

####Id
Unique identifier of the application instance
####ApplicationId
Guid of the application
####SessionKey
Guid of the session this application instance was created on (See Session property).
####StartDate
Date when the application was started
####EndDate
Date when the application was terminated
####Application
Application associated this application instance
####Session
The session associated with the application
####
Unique identifier for ApplicationInstanceSummary
####
Beginning time (to the minute) that this summary data represents The summary date.
####
Guid of the application this instance summary corresponds to (see Application property)
####
The application this summary data represents The application
####
The Id of the Delivery Group this application instance is associated with.
####
The delivery group this application instance is associated with The desktop group.
####
Number of peak concurrent instances of the application for the time slot specified The count of peak concurrent instances.
####
Total application usage duration in milliseconds for all instances of this application for the time slot specified The total duration of the application usage.
####
Total number of application launch events in the time slot
####
Number of application instances at the start of the summary window (see SummaryDate) The starting count of application instances for this period.
####
Granularity of this summary item in minutes (how many minutes of data included in this time slot) The granularity.
###Methods


####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the ApplicationInstanceSummary class.

##Monitor.Model.ApplicationInstanceSummary
            
Roll up table for Application instances
        
###Properties

####Id
Unique identifier for ApplicationInstanceSummary
####SummaryDate
Beginning time (to the minute) that this summary data represents The summary date.
####ApplicationId
Guid of the application this instance summary corresponds to (see Application property)
####Application
The application this summary data represents The application
####DesktopGroupId
The Id of the Delivery Group this application instance is associated with.
####DesktopGroup
The delivery group this application instance is associated with The desktop group.
####PeakConcurrentInstanceCount
Number of peak concurrent instances of the application for the time slot specified The count of peak concurrent instances.
####TotalUsageDuration
Total application usage duration in milliseconds for all instances of this application for the time slot specified The total duration of the application usage.
####TotalLaunchesCount
Total number of application launch events in the time slot
####StartingInstanceCount
Number of application instances at the start of the summary window (see SummaryDate) The starting count of application instances for this period.
####Granularity
Granularity of this summary item in minutes (how many minutes of data included in this time slot) The granularity.
###Methods


####Constructor
Initializes a new instance of the ApplicationInstanceSummary class.

##Monitor.Model.EntityBase
            
POCO objects base class
        
###Properties

####CreatedDate
Date this object was created
####ModifiedDate
Date this object was updated or modified
###Methods


####Constructor
Initializes a new instance of the EntityBase class.

##Monitor.Model.Catalog
            
Catalog image
        
###Properties

####Id
Unique identifier for the Catalog
####Name
Name of Catalog Broker name: CatalogName Desktop Director name: Catalog
####LifecycleState
Lifecycle state for the Catalog used for internal management and tracking
####ProvisioningType
Provisioning type for the Catalog. See Provisioning Type enum for possible values.
####PersistentUserChanges
Specifies how user changes are persisted on machines in the catalog. See Get-BrokerCatalog for details. See PersistentUserChangesType enum for possible values.
####IsMachinePhysical
Indicates whether machine is physical
####AllocationType
Denotes how the the machines in the catalog are allocated to a user. See Get-BrokerCatalog for details. See AllocationType enum for possible values.
####SessionSupport
Specifies the session support of the machines in the catalog (single vs multi) See Get-BrokerCatalog for details. See SessionSupportCode enum for possible values.
####ProvisioningSchemeId
The GUID of the provisioning scheme (if any) associated with the catalog. This only applies if the provisioning type is MCS.
####Machines
List of machines that are part of this catalog
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.DesktopOSDesktopSummary
            
Record of an instance of a running application
        
###Properties

####Id
Unique identifier of the DesktopOSDesktopSummary instance
####SummaryDate
Beginning timeslot (to the minute) that this summary data represents The summary date.
####DesktopGroupId
Guid of the DesktopGroupId this machine belongs to.
####DesktopGroup
The session associated with the application
####PeakConcurrentInstanceCount
Number of peak concurrent instances of the application for the time slot specified The count of peak concurrent instances.
####TotalUsageDuration
Total application usage duration in milliseconds for all instances of this application for the time slot specified The total duration of the application usage.
####TotalLaunchesCount
Total number of application launch events in the time slot
####StartingInstanceCount
Number of application instances at the start of the summary window (see SummaryDate) The starting count of application instances for this period.
####Granularity
Granularity of this summary item in minutes (how many minutes of data included in this time slot) The granularity.
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.ResourceUtilizationBulkInsertModel
            
Represents a resource utilization statistics of a particular machine.
        
###Properties

####CollectedDate
Date this object was created
####PercentCpu

####UsedMemory

####TotalMemory

####SessionCount

####CreatedDate
Date this object was inseretd in database
####ModifiedDate
Date this object was modifed in database
####MachineId
Guid of machine this ResourceUtilization record is associated with
####DesktopGroupId
Guid of DesktopGroup this ResourceUtilization record is associated with
###Methods


####Constructor
Initializes a new instance of the ResourceUtilizationModel class.

##Monitor.Model.ResourceUtilization
            

        
###Properties

####
Beginning timeslot (to the minute) this Summary date represent
####
Machine unique id
####
Actual Machine object
####
Guid of DesktopGroup this ResourceUtilizationSummary record is associated with
####
The DesktopGroup this ResourceUtilizationSummary record is associated with
####
Average percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####
Peak percentage of CPU for given SummaryDate Eg: Lets say CPU for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####
Average of Memory used for given SummaryDate Eg: Lets say memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Average will be calculated for above 10 records
####
Peak of Memory used for given SummaryDate Eg: Lets say Memory for this machine available at times 10:00,10:01,...,10:09 Lets say summary is calculated for every 10 minutes(i.e., granularity) SummaryDate will be 10:00 and Peak will be the highest value of above 10 records
####
Total Memory available with Machine
####
Total sessions running for given SummaryDate
####
Granularity of this summary item in minutes (how many minutes of data included in this time slot)
####
Date this object was created
####

####

####

####

####
Date this object was inseretd in database
####
Date this object was modifed in database
####
Guid of machine this ResourceUtilization record is associated with
####
Guid of DesktopGroup this ResourceUtilization record is associated with
####Machine
The machine this ResourceUtilization record is associated with
####DesktopGroup
The machine this ResourceUtilization record is associated with
###Methods


####Constructor
Initializes a new instance of the ResourceUtilizationSummary class.

####Constructor
Initializes a new instance of the ResourceUtilizationModel class.

##Monitor.Model.VShared.ConnectionFailureCategory
            
ConnectionFailureCategory, grouping for Connection failure types
        
###Properties

####Id
Unique identifier
####ConnectionFailureEnumValue
Connection failure enum value, received from the broker and cast to SessionFailureCode See the SessionFailureCode enum for possible values Connection failure enum value
####Category
Category of the failure code. See the ConnectionFailureType enum for possible values The category
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.ConnectionFailureLog
            
ConnectionFailureLog
        
###Properties

####Id
Unique identifier for ConnectionFailureLog
####SessionKey
Guid of session associated with the failure log entry
####Session
Session associated with the failure log entry. The session.
####FailureDate
Time of failure The failure time.
####ConnectionFailureEnumValue
Connection failure value. See the SessionFailureCode enum for possible values The connection failure value.
###Methods


####Constructor
Initializes a new instance of the ConnectionFailureLog class.

##Monitor.Model.Hotfix
            
Hotfix class
        
###Properties

####Id
Unique identifier of the hotfix
####Name
Name of the hotfix
####Article
URL for the article about the hotfix
####ArticleName
Name of the article
####FileName
File name of the hotfix
####FileFormat
File format of the hotfix
####Version
Version of the hotfix installed
####ComponentName
Name of the component
####ComponentVersion
Version of the component
####MachineHotfixLogs
Historical list of the all the machines that have this hotfix installed/ removed
###Methods


####Constructor
Initializes a new instance of the Hotfix class.

##Monitor.Model.Notifications.Interfaces.InstantiatedRuleChangeEventArgs
            
Fired when an instantiated rule changes
        
###Properties

####ChangeType
Gets the type of the change. The type of the change.
####ChangedRules
Gets the changed rules. The changed rules.
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.Notifications.Interfaces.ParameterMapping
            
Maps input parameters to output parameters
        
###Properties

####SourceId
Gets or sets the source identifier. The source identifier.
####TargetId
Gets or sets the target identifier. The target identifier.
###Methods


####Constructor
Initializes a new instance of the class.
> #####Parameters
> **sourceId:** The source identifier.

> **targetId:** The target identifier.


##Monitor.Model.MachineHotfixLog
            
HotfixHistory class relates the machine and hotfixes installed/ removed
        
###Properties

####Id
Unique identifier for each history entry
####MachineId
Unique identifier of the machine a hotfix has been installed to or removed form.
####HotfixId
Unique identifier of the hotfix
####ChangeType
Whether the hotfix was removed or added
####CurrentState
Is the hotfix currently installed
####Machine
Machine associated with a hotfix
####Hotfix
The hotfix associated with Machine
###Methods


####Constructor
Initializes a new instance of the MachineHotfixLog class.

##Monitor.Model.V2.Application
            
Represents a virtualized application running on a session.
        
###Properties

####Id
Unique identifier for the application
####Name
Unique administrative name of application
####PublishedName
The name published to the end user corresponding to the Broker SDK's "PublishedName" property
####ApplicationType
Type of the application, whether HostedOnDesktop or InstalledOnClient, corresponding to the ApplicationType enumeration.
####Enabled
Specifies whether or not this application can be launched.
####AdminFolder
Admin Folder
####LifecycleState
Lifecycle state for the Application user for internal tracking and deletion management.
####DesktopGroups
The Delivery groups this application is related to.
####ApplicationInstances
Set of historical instances of the application that have run or are running.
####
Unique identifier of the application instance
####
Guid of the application
####
Guid of the session this application instance was created on (See Session property).
####
Date when the application was started
####
Date when the application was terminated
####
Application associated this application instance
####
The session associated with the application
####
Unique identifier for ApplicationInstanceSummary
####
Beginning time (to the minute) that this summary data represents The summary date.
####
Guid of the application this instance summary corresponds to (see Application property)
####
The application this summary data represents The application
####
The Id of the Delivery Group this application instance is associated with.
####
The delivery group this application instance is associated with The desktop group.
####
Number of peak concurrent instances of the application for the time slot specified The count of peak concurrent instances.
####
Total application usage duration in milliseconds for all instances of this application for the time slot specified The total duration of the application usage.
####
Total number of application launch events in the time slot
####
Number of application instances at the start of the summary window (see SummaryDate) The starting count of application instances for this period.
####
Granularity of this summary item in minutes (how many minutes of data included in this time slot) The granularity.
###Methods


####Constructor
Initializes a new instance of the Application class.

####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the ApplicationInstanceSummary class.

##Monitor.Model.V2.ApplicationInstance
            
Record of an instance of a running application
        
###Properties

####Id
Unique identifier of the application instance
####ApplicationId
Guid of the application
####SessionKey
Guid of the session this application instance was created on (See Session property).
####StartDate
Date when the application was started
####EndDate
Date when the application was terminated
####Application
Application associated this application instance
####Session
The session associated with the application
####
Unique identifier for ApplicationInstanceSummary
####
Beginning time (to the minute) that this summary data represents The summary date.
####
Guid of the application this instance summary corresponds to (see Application property)
####
The application this summary data represents The application
####
The Id of the Delivery Group this application instance is associated with.
####
The delivery group this application instance is associated with The desktop group.
####
Number of peak concurrent instances of the application for the time slot specified The count of peak concurrent instances.
####
Total application usage duration in milliseconds for all instances of this application for the time slot specified The total duration of the application usage.
####
Total number of application launch events in the time slot
####
Number of application instances at the start of the summary window (see SummaryDate) The starting count of application instances for this period.
####
Granularity of this summary item in minutes (how many minutes of data included in this time slot) The granularity.
###Methods


####Constructor
Initializes a new instance of the class.

####Constructor
Initializes a new instance of the ApplicationInstanceSummary class.

##Monitor.Model.V2.ApplicationInstanceSummary
            
Roll up table for Application instances
        
###Properties

####Id
Unique identifier for ApplicationInstanceSummary
####SummaryDate
Beginning time (to the minute) that this summary data represents The summary date.
####ApplicationId
Guid of the application this instance summary corresponds to (see Application property)
####Application
The application this summary data represents The application
####DesktopGroupId
The Id of the Delivery Group this application instance is associated with.
####DesktopGroup
The delivery group this application instance is associated with The desktop group.
####PeakConcurrentInstanceCount
Number of peak concurrent instances of the application for the time slot specified The count of peak concurrent instances.
####TotalUsageDuration
Total application usage duration in milliseconds for all instances of this application for the time slot specified The total duration of the application usage.
####TotalLaunchesCount
Total number of application launch events in the time slot
####StartingInstanceCount
Number of application instances at the start of the summary window (see SummaryDate) The starting count of application instances for this period.
####Granularity
Granularity of this summary item in minutes (how many minutes of data included in this time slot) The granularity.
###Methods


####Constructor
Initializes a new instance of the ApplicationInstanceSummary class.

##Monitor.Model.V2.Catalog
            
Catalog image
        
###Properties

####Id
Unique identifier for the Catalog
####Name
Name of Catalog Broker name: CatalogName Desktop Director name: Catalog
####LifecycleState
Lifecycle state for the Catalog used for internal management and tracking
####ProvisioningType
Provisioning type for the Catalog. See Provisioning Type enum for possible values.
####PersistentUserChanges
Specifies how user changes are persisted on machines in the catalog. See Get-BrokerCatalog for details. See PersistentUserChangesType enum for possible values.
####IsMachinePhysical
Indicates whether machine is physical
####AllocationType
Denotes how the the machines in the catalog are allocated to a user. See Get-BrokerCatalog for details. See AllocationType enum for possible values.
####SessionSupport
Specifies the session support of the machines in the catalog (single vs multi) See Get-BrokerCatalog for details. See SessionSupportCode enum for possible values.
####ProvisioningSchemeId
The GUID of the provisioning scheme (if any) associated with the catalog. This only applies if the provisioning type is MCS.
####Machines
List of machines that are part of this catalog
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.V2.Connection
            
Summary collection object for session detail information - a new record will be created for every connect/reconnect on the same session All session connect data points will be captured in this class
        
###Properties

####Id
Unique identifier for Connection
####ClientName
The host name of the client connected to the session Broker name: ClientName Desktop Director name: Endpoint
####ClientAddress
The IP address of the client connected to the session Broker name: ClientAddress Desktop Director name: Endpoint (IP)
####ClientVersion
The version of the Citrix Receiver running on the client connected to the session
####ConnectedViaHostName
The host name of the incoming connection. This is usually a gateway, router or client. Broker name: ConnectedViaHostName Desktop Director name: ConnectedVia
####ConnectedViaIPAddress
The IP address of the incoming connection This is usually a gateway, router or client. Broker name: ConnectedViaIP Desktop Director name: ConnectedVia (IP)
####LaunchedViaHostName
The host name of the StoreFront server used to launch the session. Broker name: LaunchedViaHostName Desktop Director name: LaunchedVia
####LaunchedViaIPAddress
The IP address of the StoreFront server used to launch the session Broker name: LaunchedViaIP Desktop Director name: LaunchedVia (IP)
####IsReconnect
Indicates whether this connection is a reconnection to an existing session.
####IsSecureIca
Indicates whether SecureICA is active on the session. Broker name: SecureIcaActive Desktop Director name: SecureICA
####Protocol
The protocol that the session is using, can be HDX, RDP, or Console Broker name: Protocol Desktop Director name: Connection Type
####LogOnStartDate
Time stamp of Logon Start event
####LogOnEndDate
Time stamp of Logon end event
####BrokeringDuration
Brokering duration calculation
####BrokeringDate
Time stamp of Brokering time
####DisconnectCode
Disconnect event code
####DisconnectDate
Time stamp of Disconnect event
####VMStartStartDate
Time stamp of VmStartStart event maps to Brokering Time in Desktop Director UI
####VMStartEndDate
Time stamp of VmStartEnd event
####ClientSessionValidateDate
Time stamp of Client Session Validated
####ServerSessionValidateDate
Time stamp of Server Session Validated
####EstablishmentDate
Time stamp recorded on the Broker at the point when the VDA confirms session connect / reconnect maps to Resolution Time in Desktop Director UI
####HdxStartDate
Time stamp of Hdx Start event
####HdxEndDate
Time stamp of Hdx end event
####AuthenticationDuration
Authentication Duration in milliseconds
####GpoStartDate
Time stamp of GpoStart event
####GpoEndDate
Time stamp of GpoEnd event
####LogOnScriptsStartDate
Time stamp of LogonScriptsStart event
####LogOnScriptsEndDate
Time stamp of LogonScriptsEnd event
####ProfileLoadStartDate
Time stamp of ProfileLoadStart event
####ProfileLoadEndDate
Time stamp of ProfileLoadEnd event
####InteractiveStartDate
Time stamp of InteractiveStart event
####InteractiveEndDate
Time stamp of InteractiveEnd event
####SessionKey
Guid if session this connection is associated with
####Session
Session this connection is associated with
####
Unique identifier for ConnectionFailureLog
####
Guid of session associated with the failure log entry
####
Session associated with the failure log entry. The session.
####
Time of failure The failure time.
####
Connection failure value. See the SessionFailureCode enum for possible values The connection failure value.
###Methods


####Constructor
Initializes a new instance of the Connection class.

####Constructor
Initializes a new instance of the ConnectionFailureLog class.

##Monitor.Model.V2.ConnectionFailureLog
            
ConnectionFailureLog
        
###Properties

####Id
Unique identifier for ConnectionFailureLog
####SessionKey
Guid of session associated with the failure log entry
####Session
Session associated with the failure log entry. The session.
####FailureDate
Time of failure The failure time.
####ConnectionFailureEnumValue
Connection failure value. See the SessionFailureCode enum for possible values The connection failure value.
###Methods


####Constructor
Initializes a new instance of the ConnectionFailureLog class.

##Monitor.Model.V2.DesktopGroup
            
Assignment for - get-brokerdesktopgroup cmdlet
        
###Properties

####Id
Unique identifier for DesktopGroup
####Name
Desktop group name
####IsRemotePC
Remote PC indicator
####DesktopKind
Indicates if the session is shared or private. Broker name: DesktopKind Desktop Director name: Allocation Type
####LifecycleState
Internal property used for navigation and management
####SessionSupport
Specifies the session support (single/multi) of the machines in the desktop group See the SessionSupportCode for possible values. The session support.
####DeliveryType
The type of resources being published. See the enum DeliveryType for possible values.
####Machines
List of Machines that are in the desktop group
####Applications
List of Applications that are in this group
###Methods


####Constructor
Initializes a new instance of the DesktopGroup class.

##Monitor.Model.V2.FailureLogSummary
            
POCO object for failures (connection/machine) rollup/summary per minute/hour/day
        
###Properties

####Id
Unique identifier for DesktopGroupSummary
####SummaryDate
Time slot to which this summary data is assigned The summary date.
####DesktopGroupId
Guid of Delivery Group this failure log summary is associated with
####DesktopGroup
Delivery Group this failure log summary is associated with The desktop group.
####FailureCategory
Category for the failure: Connection or Machine. See FailureCategory enum for possible values. The failure category.
####FailureCode
Failure associated with this failure. See SessionFailureCode enum for possible values The type of the failure.
####FailureCount
Number of failures for this desktop group for the corresponding time interval The count of connected sessions.
####Granularity
Granularity of this summary item in minutes Length in minutes of the time slot associated with the summary data The granularity.
###Methods


####Constructor
Initializes a new instance of the FailureLogSummary class.

##Monitor.Model.V2.Hotfix
            
Hotfix class
        
###Properties

####Id
Unique identifier of the hotfix
####Name
Name of the hotfix
####Article
URL for the article about the hotfix
####ArticleName
Name of the article
####FileName
File name of the hotfix
####FileFormat
File format of the hotfix
####Version
Version of the hotfix installed
####ComponentName
Name of the component
####ComponentVersion
Version of the component
####MachineHotfixLogs
Historical list of the all the machines that have this hotfix installed/ removed
###Methods


####Constructor
Initializes a new instance of the Hotfix class.

##Monitor.Model.V2.Hypervisor
            
Assignment for - get-brokerdesktopgroup cmdlet
        
###Properties

####Id
Unique identifier for Hypervisor
####Name
Name of hypervisor
####LifecycleState
Lifecycle state for the Hypervisor - can be active or deleted See the LifecycleState enum for possible values
####Machines
Machines hosted by this hypervisor
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.V2.LoadIndex
            
Load Index collected data
        
###Properties

####Id
Unique identifier for LoadIndex
####EffectiveLoadIndex
Percentage of Total load Desktop Director name: Load Evaluator %
####Cpu
Percentage of CPU load
####Memory
Percentage of Memory load
####Disk
Percentage of Disk load
####Network
Percentage of Network load
####SessionCount
Percentage of Session Count load maps to # of Session in Desktop Director UI
####MachineId
Guid of machine this LoadIndex record is associated with
####Machine
The machine this LoadIndex record is associated with
####
Unique identifier
####
Time stamp associated with this summary data The summary date.
####
Guid of machine this summary is associated with
####
Machine this summary is associated with The machine.
####
Count of samples aggregated for each of the loadIndex parameters The Time stamp of effective load index
####
Aggregation of effective load index for this machine for the time window associated with this summary The Sum effective load index
####
Aggregation of CPU for this machine for the time window associated with this summary The Sum CPU
####
Aggregation of Network bandwidth records for this machine for the time window associated with this summary The Sum Network
####
Aggregation of Disk for this machine for this machine for the time window associated with this summary The Sum Disk
####
Aggregation of Memory for this machine for the time window associated with this summary The Sum Memory
####
Aggregation of session counts for this machine for the time window associated with this summary The Sum session count
####
Granularity of this summary item in minutes Size of the time windows in minutes for this summary The granularity.
###Methods


####Constructor
Initializes a new instance of the LoadIndex class.

####Constructor
Initializes a new instance of the LoadIndexSummary class.

##Monitor.Model.V2.LoadIndexSummary
            
POCO object for load index rollup/summary per hour/day
        
###Properties

####Id
Unique identifier
####SummaryDate
Time stamp associated with this summary data The summary date.
####MachineId
Guid of machine this summary is associated with
####Machine
Machine this summary is associated with The machine.
####SumCount
Count of samples aggregated for each of the loadIndex parameters The Time stamp of effective load index
####SumLoadIndex
Aggregation of effective load index for this machine for the time window associated with this summary The Sum effective load index
####SumCpu
Aggregation of CPU for this machine for the time window associated with this summary The Sum CPU
####SumNetwork
Aggregation of Network bandwidth records for this machine for the time window associated with this summary The Sum Network
####SumDisk
Aggregation of Disk for this machine for this machine for the time window associated with this summary The Sum Disk
####SumMemory
Aggregation of Memory for this machine for the time window associated with this summary The Sum Memory
####SumSessionCount
Aggregation of session counts for this machine for the time window associated with this summary The Sum session count
####Granularity
Granularity of this summary item in minutes Size of the time windows in minutes for this summary The granularity.
###Methods


####Constructor
Initializes a new instance of the LoadIndexSummary class.

##Monitor.Model.V2.Machine
            
Represents a Machine in the site
        
###Properties

####Id
Unique identifier for Machine
####Sid
SID of the machine
####Name
Machine name Broker name: MachineName Director name: Name
####DnsName
DNS name for this Machine, typically FQDN Broker name: DNSName Director name: DNS Name
####LifecycleState
Lifecycle state for the Machine. Used internally for data management.
####IPAddress
IP Address of the machine, can be either IP v4 or IP v6 depending on how the machine is set up Broker name: IPAddress Desktop Director name: IP Address
####HostedMachineId
Hypervisor identifier for this Machine
####HostingServerName
DNS name of the hypervisor that is hosting the machine if managed. Broker name: HostingServerName Desktop Director name: Server
####HostedMachineName
The friendly name of a hosted machine as used by its hypervisor. This is not necessarily the DNS name of the machine. Broker name: HostedMachineName Desktop Director name: VM
####IsAssigned
Denotes whether a private desktop has been assigned to a user/users, or a client name/address Broker name: IsAssigned Desktop Director name: Is Allocated
####IsInMaintenanceMode
Denotes if the machine is in maintenance mode. Broker name: InMaintenanceMode Desktop Director name: Maintenance Mode
####IsPendingUpdate
Denotes if the VM image for a hosted machine is out of date. Broker name: ImageOutOfDate Desktop Director name: Pending Update
####AgentVersion
Version of the Citrix Virtual Delivery Agent (VDA) installed on the machine. Broker name: AgentVersion Desktop Director name: Agent Version
####AssociatedUserFullNames
Full names of the users that have been associated with the machine (usually in the form "Firstname Lastname"). Associated users are the current user(s) for shared machines and the assigned users for private machines.
####AssociatedUserNames
Usernames of the users that have been associated with the machine (in the form "domain\user"). Associated users are the current user(s) for shared machines and the assigned users for private machines.
####AssociatedUserUPNs
The User Principal Names of the users associated with the machine (in the form user@domain). Associated users are the current user(s) for shared machines and the assigned users for private machines.
####CurrentRegistrationState
Current Registration state of this machine. See enum RegistrationState for possible values
####RegistrationStateChangeDate
Time stamp of change to current registation state
####LastDeregisteredCode
Last deregistration reason for this machine. See enum DeregistrationReasonCode for possible values
####LastDeregisteredDate
Time of the last machine deregistration from the controller.
####CurrentPowerState
Current power state of this machine. See enum PowerStateCode for possible values
####CurrentSessionCount
Number of sessions running on machine. Populated each minute from Session Activity consolidation task
####ControllerDnsName
The DNS host name of the controller that the machine is registered to. Can be null if not brokered.
####PoweredOnDate
Time of last powering on event for this machine
####PowerStateChangeDate
Time of change of current power state
####FunctionalLevel
Functional Level of machine See enum FunctionalLevelCode for possible values
####FailureDate
If the machine is in a failure state, the time the failure started. Otherwise, null
####WindowsConnectionSetting
The logon mode reported by Windows itself (multi-session machines only). For single-session machines the value is always hardwired to LogonEnabled. See enum WindowsConnectionSettingCode for possible values
####IsPreparing
Current PvD State of this machine (currently only used for IsPreparing value)
####FaultState
Summary state of any current fault state of the machine. See enum MachineFaultStateCode for possible values
####OSType
A string that can be used to identify the operating system that is running on the machine. Broker name: OsType Desktop Director name: OS
####CurrentLoadIndex
Most recent Load index values of machine (null if no data)
####CurrentLoadIndexId
Current LoadIndex identifier for this machine
####CatalogId
Guid of Catalog this machine belongs to
####DesktopGroupId
Guid of Delivery Group this machine belongs to
####HypervisorId
Guid of Hypervisor this machine is running on
####Catalog
Catalog this machine was created from
####DesktopGroup
Delivery group this desktop is part of
####Hypervisor
The hypervisor that this machine is associated with - can be null - not all machines are powered by hypervisors
####Sessions
List of past and present sessions for this Machine
####LoadIndex
LoadIndex values associated with this machine
####MachineFailures
Failures associated with this machine
####Hash
Holds the hash of the hotfixes on the machine
####MachineRole
Indicates whether a machine is VDA, DDC or both See the enum MachineRole for possible values
####MachineHotfixLogs
List of hotfix logs (instalation and removal) that have been applied to this machine
####
Unique identifier for machine failure log entry
####
Guid of the machine associated with the failure log entry
####
Machine associated with the failure log entry The machine.
####
Failure start time. The failure start time.
####
Failure end time. The failure end time.
####
Fault State of the machine See the enum MachineFaultStateCode for possible values
####
Last deregistration reason for this machine See the enum DeregistrationReasonCode for possible values
####
Unique identifier for each history entry
####
Unique identifier of the machine a hotfix has been installed to or removed form.
####
Unique identifier of the hotfix
####
Whether the hotfix was removed or added
####
Is the hotfix currently installed
####
Machine associated with a hotfix
####
The hotfix associated with Machine
###Methods


####Constructor
Initializes a new instance of the Machine class.

####Constructor
Initializes a new instance of the MachineFailureLog class.

####Constructor
Initializes a new instance of the MachineHotfixLog class.

##Monitor.Model.V2.MachineFailureLog
            
Represents the accumulation of machine failures
        
###Properties

####Id
Unique identifier for machine failure log entry
####MachineId
Guid of the machine associated with the failure log entry
####Machine
Machine associated with the failure log entry The machine.
####FailureStartDate
Failure start time. The failure start time.
####FailureEndDate
Failure end time. The failure end time.
####FaultState
Fault State of the machine See the enum MachineFaultStateCode for possible values
####LastDeregisteredCode
Last deregistration reason for this machine See the enum DeregistrationReasonCode for possible values
###Methods


####Constructor
Initializes a new instance of the MachineFailureLog class.

##Monitor.Model.V2.MachineHotfixLog
            
HotfixHistory class relates the machine and hotfixes installed/ removed
        
###Properties

####Id
Unique identifier for each history entry
####MachineId
Unique identifier of the machine a hotfix has been installed to or removed form.
####HotfixId
Unique identifier of the hotfix
####ChangeType
Whether the hotfix was removed or added
####CurrentState
Is the hotfix currently installed
####Machine
Machine associated with a hotfix
####Hotfix
The hotfix associated with Machine
###Methods


####Constructor
Initializes a new instance of the MachineHotfixLog class.

##Monitor.Model.V2.Session
            
Represents a user connected to a desktop.
        
###Properties

####SessionKey
Broker-assigned SessionKey for this Session
####StartDate
Time the session started (logon)
####LogOnDuration
Total log on duration for this session
####EndDate
Time the session ended (logoff)
####ExitCode
Session termination exit code
####Failure
Information on how the session failed (null if no failure)
####FailureDate
If the connection failed, the time the failure occurred. Otherwise, null
####ConnectionState
Connection State for the session. See the enum ConnectionState for possible values
####ConnectionStateChangeDate
Date of last connection state change
####LifecycleState
Lifecycle state for the Session. Used internally for tracking and management. See the enum LifecycleState for possible values.
####CurrentConnectionId
Id of the connection record currently associated with this session. May be null when session is disconnected.
####CurrentConnection
Connection record currently associated with this session.
####UserId
Id of User entry for the user logged on to this session
####User
User for the user logged on to this session maps to Last Connection User in Desktop Director UI
####MachineId
Guid of the Machine this session is running on.
####Machine
Machine this session is running on.
####SessionType
Determines if this session is from an application/ desktop. See SessionType enum for possible values
####Connections
Connections (current and past) associated with this session.
####IsAnonymous
Defines whether a session is anonymous or not
####ApplicationInstances
Application related to this session (if SessionType is 'Application')
####
Unique identifier for the session summary
####
Timestamp of the beginning of the time window that this summary data represents The summary date.
####
Guid of the desktop group this entry is associated with
####
The DesktopGroup this entry is associated with The desktop group.
####
Number of maximum connected sessions for this desktop group for the time window specified The count of connected sessions.
####
Number of maximum disconnected sessions for this desktop group for the time window specified The count of disconnected sessions.
####
Number of maximum concurrent sessions for this desktop group for the minute specified The count of Concurrent sessions.
####
Total logon duration in milliseconds for all logons in this desktop group for the time window specified The average duration of the logon.
####
Total number of logons in this desktop group for the time window specified The total log on count.
####
Granularity of the time window associated with this summary item in minutes (how many minutes of data included in this record) The granularity.
###Methods


####Constructor
Initializes a new instance of the Session class.

####Constructor
Initializes a new instance of the SessionActivitySummary class.

##Monitor.Model.V2.SessionActivitySummary
            
POCO object for session activity consolidation
        
###Properties

####Id
Unique identifier for the session summary
####SummaryDate
Timestamp of the beginning of the time window that this summary data represents The summary date.
####DesktopGroupId
Guid of the desktop group this entry is associated with
####DesktopGroup
The DesktopGroup this entry is associated with The desktop group.
####ConnectedSessionCount
Number of maximum connected sessions for this desktop group for the time window specified The count of connected sessions.
####DisconnectedSessionCount
Number of maximum disconnected sessions for this desktop group for the time window specified The count of disconnected sessions.
####ConcurrentSessionCount
Number of maximum concurrent sessions for this desktop group for the minute specified The count of Concurrent sessions.
####TotalLogOnDuration
Total logon duration in milliseconds for all logons in this desktop group for the time window specified The average duration of the logon.
####TotalLogOnCount
Total number of logons in this desktop group for the time window specified The total log on count.
####Granularity
Granularity of the time window associated with this summary item in minutes (how many minutes of data included in this record) The granularity.
###Methods


####Constructor
Initializes a new instance of the SessionActivitySummary class.

##Monitor.Model.V2.TaskLog
            
Represents the task execution log
        
###Properties

####Id
Unique identifier for TaskLog entry
####RunDate
Time stamp indicating when the task was started The run date.
####TaskCategory
Category of the task run. See the TaskCategory enum for possible values The task category.
####Task
Specific task that was run. See the DataManagementTask enum for possible values The task.
####Result
Result from having run the task. See the TaskResult enum for possible values The result.
####ErrorMessage
Empty if task ran successsfully, otherwise a string describing the error that occurred. The error message.

##Monitor.Model.V2.User
            
Represents a user in the system
        
###Properties

####Id
Unique identifier for the User
####Sid
Security Identifier for the user.
####Upn
User Principal Name - has two parts: the UPN prefix (the user account name) and the UPN suffix (a DNS domain name). The parts are joined together by the at sign (@) symbol to make the complete UPN. Broker name: AssociatedUserUpns DesktopDirector name: UserUpn
####UserName
Username in the form of DOMAIN\UserName
####FullName
Full name of the user.
####Domain
Domain the user is associated with
####Sessions
List of past and present sessions for this User
###Methods


####Constructor
Default constructor

##Monitor.Model.ServerOSDesktopSummary
            
Record of an instance of a running application
        
###Properties

####Id
Unique identifier of the ServerOSDesktopSummary instance
####SummaryDate
Beginning timeslot (to the minute) that this summary data represents The summary date.
####MachineId
Guid of the Desktop
####Machine
Machine associated this session
####DesktopGroupId
Guid of the DesktopGroupId this machine belongs to.
####DesktopGroup
The session associated with the application
####PeakConcurrentInstanceCount
Number of peak concurrent instances of the application for the time slot specified The count of peak concurrent instances.
####TotalUsageDuration
Total application usage duration in milliseconds for all instances of this application for the time slot specified The total duration of the application usage.
####TotalLaunchesCount
Total number of application launch events in the time slot
####StartingInstanceCount
Number of application instances at the start of the summary window (see SummaryDate) The starting count of application instances for this period.
####Granularity
Granularity of this summary item in minutes (how many minutes of data included in this time slot) The granularity.
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.TaskLog
            
Represents the task execution log
        
###Properties

####Id
Unique identifier for TaskLog entry
####RunDate
Time stamp indicating when the task was started The run date.
####TaskCategory
Category of the task run. See the TaskCategory enum for possible values The task category.
####Task
Specific task that was run. See the DataManagementTask enum for possible values The task.
####Result
Result from having run the task. See the TaskResult enum for possible values The result.
####ErrorMessage
Empty if task ran successsfully, otherwise a string describing the error that occurred. The error message.

##Monitor.Model.LoadIndexSummary
            
POCO object for load index rollup/summary per hour/day
        
###Properties

####Id
Unique identifier
####SummaryDate
Time stamp associated with this summary data The summary date.
####MachineId
Guid of machine this summary is associated with
####Machine
Machine this summary is associated with The machine.
####SumCount
Count of samples aggregated for each of the loadIndex parameters The Time stamp of effective load index
####SumLoadIndex
Aggregation of effective load index for this machine for the time window associated with this summary The Sum effective load index
####SumCpu
Aggregation of CPU for this machine for the time window associated with this summary The Sum CPU
####SumNetwork
Aggregation of Network bandwidth records for this machine for the time window associated with this summary The Sum Network
####SumDisk
Aggregation of Disk for this machine for this machine for the time window associated with this summary The Sum Disk
####SumMemory
Aggregation of Memory for this machine for the time window associated with this summary The Sum Memory
####SumSessionCount
Aggregation of session counts for this machine for the time window associated with this summary The Sum session count
####Granularity
Granularity of this summary item in minutes Size of the time windows in minutes for this summary The granularity.
###Methods


####Constructor
Initializes a new instance of the LoadIndexSummary class.

##Monitor.Model.FailureLogSummary
            
POCO object for failures (connection/machine) rollup/summary per minute/hour/day
        
###Properties

####Id
Unique identifier for DesktopGroupSummary
####SummaryDate
Time slot to which this summary data is assigned The summary date.
####DesktopGroupId
Guid of Delivery Group this failure log summary is associated with
####DesktopGroup
Delivery Group this failure log summary is associated with The desktop group.
####FailureCategory
Category for the failure: Connection or Machine. See FailureCategory enum for possible values. The failure category.
####FailureCode
Failure associated with this failure. See SessionFailureCode enum for possible values The type of the failure.
####FailureCount
Number of failures for this desktop group for the corresponding time interval The count of connected sessions.
####Granularity
Granularity of this summary item in minutes Length in minutes of the time slot associated with the summary data The granularity.
###Methods


####Constructor
Initializes a new instance of the FailureLogSummary class.

##Monitor.Model.Hypervisor
            
Assignment for - get-brokerdesktopgroup cmdlet
        
###Properties

####Id
Unique identifier for Hypervisor
####Name
Name of hypervisor
####LifecycleState
Lifecycle state for the Hypervisor - can be active or deleted See the LifecycleState enum for possible values
####Machines
Machines hosted by this hypervisor
###Methods


####Constructor
Initializes a new instance of the class.

##Monitor.Model.LoadIndex
            
Load Index collected data
        
###Properties

####
Unique identifier
####
Time stamp associated with this summary data The summary date.
####
Guid of machine this summary is associated with
####
Machine this summary is associated with The machine.
####
Count of samples aggregated for each of the loadIndex parameters The Time stamp of effective load index
####
Aggregation of effective load index for this machine for the time window associated with this summary The Sum effective load index
####
Aggregation of CPU for this machine for the time window associated with this summary The Sum CPU
####
Aggregation of Network bandwidth records for this machine for the time window associated with this summary The Sum Network
####
Aggregation of Disk for this machine for this machine for the time window associated with this summary The Sum Disk
####
Aggregation of Memory for this machine for the time window associated with this summary The Sum Memory
####
Aggregation of session counts for this machine for the time window associated with this summary The Sum session count
####
Granularity of this summary item in minutes Size of the time windows in minutes for this summary The granularity.
####Id
Unique identifier for LoadIndex
####EffectiveLoadIndex
Percentage of Total load Desktop Director name: Load Evaluator %
####Cpu
Percentage of CPU load
####Memory
Percentage of Memory load
####Disk
Percentage of Disk load
####Network
Percentage of Network load
####SessionCount
Percentage of Session Count load maps to # of Session in Desktop Director UI
####MachineId
Guid of machine this LoadIndex record is associated with
####Machine
The machine this LoadIndex record is associated with
###Methods


####Constructor
Initializes a new instance of the LoadIndexSummary class.

####Constructor
Initializes a new instance of the LoadIndex class.

##Monitor.Model.MachineFailureLog
            
Represents the accumulation of machine failures
        
###Properties

####Id
Unique identifier for machine failure log entry
####MachineId
Guid of the machine associated with the failure log entry
####Machine
Machine associated with the failure log entry The machine.
####FailureStartDate
Failure start time. The failure start time.
####FailureEndDate
Failure end time. The failure end time.
####FaultState
Fault State of the machine See the enum MachineFaultStateCode for possible values
####LastDeregisteredCode
Last deregistration reason for this machine See the enum DeregistrationReasonCode for possible values
###Methods


####Constructor
Initializes a new instance of the MachineFailureLog class.

##Monitor.Model.DesktopGroup
            
Assignment for - get-brokerdesktopgroup cmdlet
        
###Properties

####Id
Unique identifier for DesktopGroup
####Name
Desktop group name
####IsRemotePC
Remote PC indicator
####DesktopKind
Indicates if the session is shared or private. Broker name: DesktopKind Desktop Director name: Allocation Type
####LifecycleState
Internal property used for navigation and management
####SessionSupport
Specifies the session support (single/multi) of the machines in the desktop group See the SessionSupportCode for possible values. The session support.
####DeliveryType
The type of resources being published. See the enum DeliveryType for possible values.
####IsInMaintenanceMode
Maintenance mode indicator
####Machines
List of Machines that are in the desktop group
####Applications
List of Applications that are in this group
####ResourceUtilization
ResourceUtilization values associated with this Desktop Group
####ResourceUtilizationSummary
ResourceUtilizationSummary values associated with this Desktop Group
###Methods


####Constructor
Initializes a new instance of the DesktopGroup class.

##Monitor.Model.SessionActivitySummary
            
POCO object for session activity consolidation
        
###Properties

####Id
Unique identifier for the session summary
####SummaryDate
Timestamp of the beginning of the time window that this summary data represents The summary date.
####DesktopGroupId
Guid of the desktop group this entry is associated with
####DesktopGroup
The DesktopGroup this entry is associated with The desktop group.
####ConnectedSessionCount
Number of maximum connected sessions for this desktop group for the time window specified The count of connected sessions.
####DisconnectedSessionCount
Number of maximum disconnected sessions for this desktop group for the time window specified The count of disconnected sessions.
####ConcurrentSessionCount
Number of maximum concurrent sessions for this desktop group for the minute specified The count of Concurrent sessions.
####TotalLogOnDuration
Total logon duration in milliseconds for all logons in this desktop group for the time window specified The average duration of the logon.
####TotalLogOnCount
Total number of logons in this desktop group for the time window specified The total log on count.
####Granularity
Granularity of the time window associated with this summary item in minutes (how many minutes of data included in this record) The granularity.
###Methods


####Constructor
Initializes a new instance of the SessionActivitySummary class.

##Monitor.Model.Connection
            
Summary collection object for session detail information - a new record will be created for every connect/reconnect on the same session All session connect data points will be captured in this class
        
###Properties

####
Unique identifier for ConnectionFailureLog
####
Guid of session associated with the failure log entry
####
Session associated with the failure log entry. The session.
####
Time of failure The failure time.
####
Connection failure value. See the SessionFailureCode enum for possible values The connection failure value.
####Id
Unique identifier for Connection
####ClientName
The host name of the client connected to the session Broker name: ClientName Desktop Director name: Endpoint
####ClientAddress
The IP address of the client connected to the session Broker name: ClientAddress Desktop Director name: Endpoint (IP)
####ClientVersion
The version of the Citrix Receiver running on the client connected to the session
####ClientPlatform
The platform running on the client.
####ConnectedViaHostName
The host name of the incoming connection. This is usually a gateway, router or client. Broker name: ConnectedViaHostName Desktop Director name: ConnectedVia
####ConnectedViaIPAddress
The IP address of the incoming connection This is usually a gateway, router or client. Broker name: ConnectedViaIP Desktop Director name: ConnectedVia (IP)
####LaunchedViaHostName
The host name of the StoreFront server used to launch the session. Broker name: LaunchedViaHostName Desktop Director name: LaunchedVia
####LaunchedViaIPAddress
The IP address of the StoreFront server used to launch the session Broker name: LaunchedViaIP Desktop Director name: LaunchedVia (IP)
####IsReconnect
Indicates whether this connection is a reconnection to an existing session.
####IsSecureIca
Indicates whether SecureICA is active on the session. Broker name: SecureIcaActive Desktop Director name: SecureICA
####Protocol
The protocol that the session is using, can be HDX, RDP, or Console Broker name: Protocol Desktop Director name: Connection Type
####LogOnStartDate
Time stamp of Logon Start event
####LogOnEndDate
Time stamp of Logon end event
####BrokeringDuration
Brokering duration calculation
####BrokeringDate
Time stamp of Brokering time
####DisconnectCode
Disconnect event code
####DisconnectDate
Time stamp of Disconnect event
####VMStartStartDate
Time stamp of VmStartStart event maps to Brokering Time in Desktop Director UI
####VMStartEndDate
Time stamp of VmStartEnd event
####ClientSessionValidateDate
Time stamp of Client Session Validated
####ServerSessionValidateDate
Time stamp of Server Session Validated
####EstablishmentDate
Time stamp recorded on the Broker at the point when the VDA confirms session connect / reconnect maps to Resolution Time in Desktop Director UI
####HdxStartDate
Time stamp of Hdx Start event
####HdxEndDate
Time stamp of Hdx end event
####AuthenticationDuration
Authentication Duration in milliseconds
####GpoStartDate
Time stamp of GpoStart event
####GpoEndDate
Time stamp of GpoEnd event
####LogOnScriptsStartDate
Time stamp of LogonScriptsStart event
####LogOnScriptsEndDate
Time stamp of LogonScriptsEnd event
####ProfileLoadStartDate
Time stamp of ProfileLoadStart event
####ProfileLoadEndDate
Time stamp of ProfileLoadEnd event
####InteractiveStartDate
Time stamp of InteractiveStart event
####InteractiveEndDate
Time stamp of InteractiveEnd event
####SessionKey
Guid if session this connection is associated with
####Session
Session this connection is associated with
###Methods


####Constructor
Initializes a new instance of the ConnectionFailureLog class.

####Constructor
Initializes a new instance of the Connection class.

##Monitor.Model.Machine
            
Represents a Machine in the site
        
###Properties

####
Date this object was created
####
Iops on the machine
####
Latency on the machine
####
Guid of machine this MachineMetric record is associated with
####
The machine this MachineMetric record is associated with
####
Beginning timeslot (to the minute) this Summary date represent
####
Machine unique id
####
Actual Machine object
####
Average IOPS for given SummaryDate Eg: Lets say iops for this machine available at times 10:00,11:00,...,21:00 Lets say summary is calculated for every 1 DAY(i.e., granularity) SummaryDate will be DAY x 00:00 and Average will be calculated for above records
####
Peak IOPS given SummaryDate Eg: Lets say iops for this machine available at times 10:00,11:00,...,21:00 Lets say summary is calculated for every 1 DAY(i.e., granularity) SummaryDate will be DAY x 00:00 and Peak will be calculated for above records
####
Average Latency on the machine for given SummaryDate
####
Unique identifier for each history entry
####
Unique identifier of the machine a hotfix has been installed to or removed form.
####
Unique identifier of the hotfix
####
Whether the hotfix was removed or added
####
Is the hotfix currently installed
####
Machine associated with a hotfix
####
The hotfix associated with Machine
####
Unique identifier for machine failure log entry
####
Guid of the machine associated with the failure log entry
####
Machine associated with the failure log entry The machine.
####
Failure start time. The failure start time.
####
Failure end time. The failure end time.
####
Fault State of the machine See the enum MachineFaultStateCode for possible values
####
Last deregistration reason for this machine See the enum DeregistrationReasonCode for possible values
####Id
Unique identifier for Machine
####Sid
SID of the machine
####Name
Machine name Broker name: MachineName Director name: Name
####DnsName
DNS name for this Machine, typically FQDN Broker name: DNSName Director name: DNS Name
####LifecycleState
Lifecycle state for the Machine. Used internally for data management.
####IPAddress
IP Address of the machine, can be either IP v4 or IP v6 depending on how the machine is set up Broker name: IPAddress Desktop Director name: IP Address
####HostedMachineId
Hypervisor identifier for this Machine
####HostingServerName
DNS name of the hypervisor that is hosting the machine if managed. Broker name: HostingServerName Desktop Director name: Server
####HostedMachineName
The friendly name of a hosted machine as used by its hypervisor. This is not necessarily the DNS name of the machine. Broker name: HostedMachineName Desktop Director name: VM
####IsAssigned
Denotes whether a private desktop has been assigned to a user/users, or a client name/address Broker name: IsAssigned Desktop Director name: Is Allocated
####IsInMaintenanceMode
Denotes if the machine is in maintenance mode. Broker name: InMaintenanceMode Desktop Director name: Maintenance Mode
####IsPendingUpdate
Denotes if the VM image for a hosted machine is out of date. Broker name: ImageOutOfDate Desktop Director name: Pending Update
####AgentVersion
Version of the Citrix Virtual Delivery Agent (VDA) installed on the machine. Broker name: AgentVersion Desktop Director name: Agent Version
####AssociatedUserFullNames
Full names of the users that have been associated with the machine (usually in the form "Firstname Lastname"). Associated users are the current user(s) for shared machines and the assigned users for private machines.
####AssociatedUserNames
Usernames of the users that have been associated with the machine (in the form "domain\user"). Associated users are the current user(s) for shared machines and the assigned users for private machines.
####AssociatedUserUPNs
The User Principal Names of the users associated with the machine (in the form user@domain). Associated users are the current user(s) for shared machines and the assigned users for private machines.
####CurrentRegistrationState
Current Registration state of this machine. See enum RegistrationState for possible values
####RegistrationStateChangeDate
Time stamp of change to current registation state
####LastDeregisteredCode
Last deregistration reason for this machine. See enum DeregistrationReasonCode for possible values
####LastDeregisteredDate
Time of the last machine deregistration from the controller.
####CurrentPowerState
Current power state of this machine. See enum PowerStateCode for possible values
####CurrentSessionCount
Number of sessions running on machine. Populated each minute from Session Activity consolidation task
####ControllerDnsName
The DNS host name of the controller that the machine is registered to. Can be null if not brokered.
####PoweredOnDate
Time of last powering on event for this machine
####PowerStateChangeDate
Time of change of current power state
####FunctionalLevel
Functional Level of machine See enum FunctionalLevelCode for possible values
####FailureDate
If the machine is in a failure state, the time the failure started. Otherwise, null
####WindowsConnectionSetting
The logon mode reported by Windows itself (multi-session machines only). For single-session machines the value is always hardwired to LogonEnabled. See enum WindowsConnectionSettingCode for possible values
####IsPreparing
Current PvD State of this machine (currently only used for IsPreparing value)
####FaultState
Summary state of any current fault state of the machine. See enum MachineFaultStateCode for possible values
####OSType
A string that can be used to identify the operating system that is running on the machine. Broker name: OsType Desktop Director name: OS
####CurrentLoadIndex
Most recent Load index values of machine (null if no data)
####CurrentLoadIndexId
Current LoadIndex identifier for this machine
####CatalogId
Guid of Catalog this machine belongs to
####DesktopGroupId
Guid of Delivery Group this machine belongs to
####HypervisorId
Guid of Hypervisor this machine is running on
####Catalog
Catalog this machine was created from
####DesktopGroup
Delivery group this desktop is part of
####Hypervisor
The hypervisor that this machine is associated with - can be null - not all machines are powered by hypervisors
####Sessions
List of past and present sessions for this Machine
####LoadIndex
LoadIndex values associated with this machine
####ResourceUtilization
ResourceUtilization values associated with this machine
####ProcessInfo
ProcessInfo values associated with this machine
####ProcessUtilization
ProcessUtilization values associated with this machine
####ProcessUtilizationMinuteSummary
ProcessUtilizationMinuteSummary values associated with this machine
####ProcessUtilizationHourSummary
ProcessUtilizationHourSummary values associated with this machine
####ProcessUtilizationDaySummary
ProcessUtilizationDaySummary values associated with this machine
####MachineFailures
Failures associated with this machine
####MachineMetric
IOPS Utilization values associated with this machine
####MachineMetricSummary
IOPS Utilization values associated with this machine
####Hash
Holds the hash of the hotfixes on the machine
####MachineRole
Indicates whether a machine is VDA, DDC or both See the enum MachineRole for possible values
####MachineHotfixLogs
List of hotfix logs (instalation and removal) that have been applied to this machine
####ApplicationFaults
Application faults associated wth this machine
####ApplicationErrors
Application errors associated wth this machine
###Methods


####Constructor
Initializes a new instance of the MachineMetricBulkInsertModel class.

####Constructor
Initializes a new instance of the MachineMetricDaySummary class.

####Constructor
Initializes a new instance of the MachineHotfixLog class.

####Constructor
Initializes a new instance of the MachineFailureLog class.

####Constructor
Initializes a new instance of the Machine class.

##Monitor.Model.Session
            
Represents a user connected to a desktop.
        
###Properties

####
Autogenerated id for Session Metrics record
####
Date this object was collected from source
####

####
Date this object was created in database
####
Date this object was modified in database
####
Guid of machine this SessionMetrics record is associated with
####
The machine this ResourceUtilization record is associated with
####
Unique identifier for the session summary
####
Timestamp of the beginning of the time window that this summary data represents The summary date.
####
Guid of the desktop group this entry is associated with
####
The DesktopGroup this entry is associated with The desktop group.
####
Number of maximum connected sessions for this desktop group for the time window specified The count of connected sessions.
####
Number of maximum disconnected sessions for this desktop group for the time window specified The count of disconnected sessions.
####
Number of maximum concurrent sessions for this desktop group for the minute specified The count of Concurrent sessions.
####
Total logon duration in milliseconds for all logons in this desktop group for the time window specified The average duration of the logon.
####
Total number of logons in this desktop group for the time window specified The total log on count.
####
Granularity of the time window associated with this summary item in minutes (how many minutes of data included in this record) The granularity.
####SessionKey
Broker-assigned SessionKey for this Session
####StartDate
Time the session started (logon)
####LogOnDuration
Total log on duration for this session
####EndDate
Time the session ended (logoff)
####ExitCode
Session termination exit code
####Failure
Information on how the session failed (null if no failure)
####FailureDate
If the connection failed, the time the failure occurred. Otherwise, null
####ConnectionState
Connection State for the session. See the enum ConnectionState for possible values
####SessionIdleTime
Session idle time since
####ConnectionStateChangeDate
Date of last connection state change
####LifecycleState
Lifecycle state for the Session. Used internally for tracking and management. See the enum LifecycleState for possible values.
####CurrentConnectionId
Id of the connection record currently associated with this session. May be null when session is disconnected.
####CurrentConnection
Connection record currently associated with this session.
####UserId
Id of User entry for the user logged on to this session
####User
User for the user logged on to this session maps to Last Connection User in Desktop Director UI
####MachineId
Guid of the Machine this session is running on.
####Machine
Machine this session is running on.
####SessionType
Determines if this session is from an application/ desktop. See SessionType enum for possible values
####Connections
Connections (current and past) associated with this session.
####ConnectionFailureLogs
Connection failures (current and past) associated with this session.
####SessionMetrics
SessionMetrics values associated with this session
####Processes
ProcessInfo object associated with this session
####IsAnonymous
Defines whether a session is anonymous or not
####ApplicationInstances
Application related to this session (if SessionType is 'Application')
####ApplicationFaults
Application faults associated wth this session
####ApplicationErrors
Application errors associated wth this session
###Methods


####Constructor
Initializes a new instance of the SessionMetricsBulkInsertModel class.

####Constructor
Initializes a new instance of the SessionActivitySummary class.

####Constructor
Initializes a new instance of the Session class.

##Monitor.Model.User
            
Represents a user in the system
        
###Properties

####Id
Unique identifier for the User
####Sid
Security Identifier for the user.
####Upn
User Principal Name - has two parts: the UPN prefix (the user account name) and the UPN suffix (a DNS domain name). The parts are joined together by the at sign (@) symbol to make the complete UPN. Broker name: AssociatedUserUpns DesktopDirector name: UserUpn
####UserName
Username in the form of DOMAIN\UserName
####FullName
Full name of the user.
####Domain
Domain the user is associated with
####Sessions
List of past and present sessions for this User
###Methods


####Constructor
Default constructor

##Monitor.Model.V1.Catalog
            
Catalog image
        
###Properties

####Id
unique identifier for Catalog
####Name
Broker name: CatalogName Desktop Director name: Catalog
####LifecycleState
Lifecycle state for the Catalog
####ProvisioningType
provisioning type for the Catalog
####PersistentUserChanges
provisioning type for the Catalog
####IsMachinePhysical
physical machine indicator
####AllocationType
provisioning type for the Catalog
####SessionSupport
provisioning type for the Catalog
####ProvisioningSchemeId
Provisioning Scheme Id is used by MCS to identify a Catalog
####Machines
Group of virtual desktops using this catalog

##Monitor.Model.V1.ConnectionFailureLog
            
ConnectionFailureLog
        
###Properties

####Id
unique identifier for ConnectionFailureLog
####SessionKey
Foreign key associating this ConnectionFailureLog record with a Session
####Session
Gets or sets the session. The session.
####FailureDate
Gets or sets the failure time. The failure time.
####ConnectionFailureEnumValue
Gets or sets the connection failure value - this is the value of the SessionFailureCode enum from the Broker. The connection failure value.

##Monitor.Model.V1.LoadIndexSummary
            
POCO object for load index rollup/summary per hour/day
        
###Properties

####Id
unique identifier for DesktopGroupSummary
####SummaryDate
Timeslot to the minute that this summary data represents The summary date.
####MachineId
Foreign key associating this LoadIndexSummary record with a Machine
####Machine
The machine this summary data represents The machine.
####AverageLoadIndex
Average effective load index for this machine for the hour/day specified The average effective load index
####AverageCpu
Average CPU for this machine for the hour/day specified The average CPU
####AverageNetwork
Average Network for this machine for the hour/day specified The average Network
####AverageDisk
Average Disk for this machine for the hour/day specified The average Disk
####AverageMemory
Average Memory for this machine for the hour/day specified The average Memory
####AverageSessionCount
Average session count for this machine for the hour/day specified The average session count
####Granularity
Granularity of this summary item in minutes (how many minutes of data included in this record) The granularity.

##Monitor.Model.V1.FailureLogSummary
            
POCO object for failures (connection/machine) rollup/summary per minute/hour/day
        
###Properties

####Id
unique identifier for DesktopGroupSummary
####SummaryDate
Timeslot to the minute that this summary data represents The summary date.
####DesktopGroupId
Foreign key associating this FailureLogSummary record with a DesktopGroup
####DesktopGroup
The desktop group this summary data represents The desktop group.
####FailureCategory
Category for the failure: Connection or Machine; corresponds to FailureCategory enum. The failure category.
####FailureCode
Failure code will correspond to the broker value (from op events or polling) The type of the failure.
####FailureCount
Number of maximum connected sessions for this desktop group for the minute specified The count of connected sessions.
####Granularity
Granularity of this summary item in minutes (how many minutes of data included in this record) The granularity.

##Monitor.Model.V1.Hypervisor
            
Assignment for - get-brokerdesktopgroup cmdlet
        
###Properties

####Id
unique identifier for Hypervisor
####Name
Desktop group name
####LifecycleState
Lifecycle state for the Hypervisor - can be active or deleted
####Machines
Machines that are in this powered by this hypervisor

##Monitor.Model.V1.LoadIndex
            
Load Index collected data
        
###Properties

####
unique identifier for DesktopGroupSummary
####
Timeslot to the minute that this summary data represents The summary date.
####
Foreign key associating this LoadIndexSummary record with a Machine
####
The machine this summary data represents The machine.
####
Average effective load index for this machine for the hour/day specified The average effective load index
####
Average CPU for this machine for the hour/day specified The average CPU
####
Average Network for this machine for the hour/day specified The average Network
####
Average Disk for this machine for the hour/day specified The average Disk
####
Average Memory for this machine for the hour/day specified The average Memory
####
Average session count for this machine for the hour/day specified The average session count
####
Granularity of this summary item in minutes (how many minutes of data included in this record) The granularity.
####Id
unique identifier for RdsLoadIndex
####EffectiveLoadIndex
Percentage of Total load Desktop Director name: Load Evaluator %
####Cpu
Percentage of CPU load
####Memory
Percentage of Memory load
####Disk
Percentage of Disk load
####Network
Percentage of Network load
####SessionCount
Percentage of Session Count load maps to # of Session in Desktop Director UI
####MachineId
Foreign key associating this LoadIndex record with a Machine
####Machine
The machine the load was measured on

##Monitor.Model.V1.MachineFailureLog
            
MachineFailureLog
        
###Properties

####Id
unique identifier for MachineFailureLog
####MachineId
Foreign key associating this MachineFailureLog record with a Machine
####Machine
Gets or sets the machine. The machine.
####FailureStartDate
Gets or sets the failure start time. The failure start time.
####FailureEndDate
Gets or sets the failure end time. The failure end time.
####FaultState
Fault State of the machine
####LastDeregisteredCode
Last deregistration reason for this machine

##Monitor.Model.V1.DesktopGroup
            
Assignment for - get-brokerdesktopgroup cmdlet
        
###Properties

####Id
unique identifier for DesktopGroup
####Name
Desktop group name
####IsRemotePC
remote pc flag
####DesktopKind
Broker name: DesktopKind Desktop Director name: Allocation Type
####LifecycleState
Lifecycle state for the DesktopGroup - can be active or deleted
####SessionSupport
Session support - RDS or VDI for this desktop group The session support.
####Machines
Machines that are in this group

##Monitor.Model.V1.SessionActivitySummary
            
POCO object for session activity consolidation
        
###Properties

####Id
unique identifier for DesktopGroupSummary
####SummaryDate
Timeslot to the minute that this summary data represents The summary date.
####DesktopGroupId
Foreign key associating this SessionActivitySummary record with a DesktopGroup
####DesktopGroup
The desktop group this summary data represents The desktop group.
####ConnectedSessionCount
Number of maximum connected sessions for this desktop group for the minute specified The count of connected sessions.
####DisconnectedSessionCount
Number of maximum disconnected sessions for this desktop group for the minute specified The count of disconnected sessions.
####ConcurrentSessionCount
Number of maximum concurrent sessions for this desktop group for the minute specified The count of Concurrent sessions.
####TotalLogOnDuration
Total logon duration in milliseconds for all logons in this desktop group for the minute specified The average duration of the logon.
####TotalLogOnCount
Total number of logons in this desktop group for the minute specified The total log on count.
####Granularity
Granularity of this summary item in minutes (how many minutes of data included in this record) The granularity.

##Monitor.Model.V1.Connection
            
summary collection object for session detail information - a new record will be created for every connect/reconnect on the same session ALL session connect data points will be captured in this class
        
###Properties

####
unique identifier for ConnectionFailureLog
####
Foreign key associating this ConnectionFailureLog record with a Session
####
Gets or sets the session. The session.
####
Gets or sets the failure time. The failure time.
####
Gets or sets the connection failure value - this is the value of the SessionFailureCode enum from the Broker. The connection failure value.
####Id
unique identifier for Connection
####ClientName
Broker name: ClientName Desktop Director name: Endpoint
####ClientAddress
Broker name: ClientAddress Desktop Director name: Endpoint (IP)
####ClientVersion
Client Version maps to Plug-In Version in Desktop Director UI
####ConnectedViaHostName
Broker name: ConnectedViaHostName Desktop Director name: ConnectedVia
####ConnectedViaIPAddress
Broker name: ConnectedViaIP Desktop Director name: ConnectedVia (IP)
####LaunchedViaHostName
Broker name: LaunchedViaHostName Desktop Director name: LaunchedVia
####LaunchedViaIPAddress
Broker name: LaunchedViaIP Desktop Director name: LaunchedVia (IP)
####IsReconnect
This is a reconnect detail record
####IsSecureIca
Broker name: SecureIcaActive Desktop Director name: SecureICA
####Protocol
Broker name: Protocol Desktop Director name: Connection Type
####LogOnStartDate
DateTime? for Logon Start event
####LogOnEndDate
DateTime? for Logon end event
####BrokeringDuration
Brokering duration calculation
####BrokeringDate
DateTime? for Brokering time
####DisconnectCode
Disconnect event code
####DisconnectDate
DateTime? for Disconnect event
####VMStartStartDate
DateTime? for VmStartStart event maps to Brokering Time in Desktop Director UI
####VMStartEndDate
DateTime? for VmStartEnd event
####ClientSessionValidateDate
DateTime? for Client Session Validated
####ServerSessionValidateDate
DateTime? for Server Session Validated
####EstablishmentDate
DateTime? recorded at the Broker at the point when the VDA confirms session connect / reconnect maps to Resolution Time in Desktop Director UI
####HdxStartDate
DateTime? for Hdx Start event
####HdxEndDate
DateTime? for Hdx end event
####AuthenticationDuration
Int32? for AuthenticationDuration event
####GpoStartDate
DateTime? for GpoStart event
####GpoEndDate
DateTime? for GpoEnd event
####LogOnScriptsStartDate
DateTime? for LogonScriptsStart event
####LogOnScriptsEndDate
DateTime? for LogonScriptsEnd event
####ProfileLoadStartDate
DateTime? for ProfileLoadStart event
####ProfileLoadEndDate
DateTime? for ProfileLoadEnd event
####InteractiveStartDate
DateTime? for InteractiveStart event
####InteractiveEndDate
DateTime? for InteractiveEnd event
####SessionKey
Foreign key associating this Connection record with a Session
####Session
The session this detail record is tied to
###Methods


####Constructor
constructor

##Monitor.Model.V1.Machine
            
Machine class
        
###Properties

####
unique identifier for MachineFailureLog
####
Foreign key associating this MachineFailureLog record with a Machine
####
Gets or sets the machine. The machine.
####
Gets or sets the failure start time. The failure start time.
####
Gets or sets the failure end time. The failure end time.
####
Fault State of the machine
####
Last deregistration reason for this machine
####Id
unique identifier for Machine
####Sid
WorkerSID
####Name
Machine name Broker name: MachineName Director name: Name
####DnsName
DNS name for this Machine, typically FQDN Broker name: DNSName Director name: DNS Name
####LifecycleState
Lifecycle state for the Machine
####IPAddress
IP Address of the machine, can be either IP v4 or IP v6 depending on how the machine is set up Broker name: IPAddress Desktop Director name: IP Address
####HostedMachineId
HostedMachineID Hypervisor identifier for this Machine
####HostingServerName
Broker name: HostingServerName Desktop Director name: Server
####HostedMachineName
Broker name: HostedMachineName Desktop Director name: VM
####IsAssigned
Broker name: IsAssigned Desktop Director name: Is Allocated
####IsInMaintenanceMode
Broker name: InMaintenanceMode Desktop Director name: Maintenance Mode
####IsPendingUpdate
Broker name: ImageOutOfDate Desktop Director name: Pending Update
####AgentVersion
Broker name: AgentVersion Desktop Director name: Agent Version
####AssociatedUserFullNames
Comma separated list of full names for associated users assigned to this machine
####AssociatedUserNames
Comma separated list of user names for associated users assigned to this machine
####AssociatedUserUPNs
Comma separated list of UPNs for associated users assigned to this machine
####CurrentRegistrationState
Current Registration state of this machine
####RegistrationStateChangeDate
datetime of change of current registation state
####LastDeregisteredCode
Last deregistration reason for this machine
####LastDeregisteredDate
Datetime of change of last deregistation
####CurrentPowerState
current power state of this machine
####CurrentSessionCount
Populated each minute from Session Activity consolidation task
####ControllerDnsName
Broker that registered this machine. Can be null if not brokered.
####PoweredOnDate
Datetime of last powering on event for this machine
####PowerStateChangeDate
datetime of change of current power state
####FunctionalLevel
Functional Level
####FailureDate
If the machine is in a failure state, the time the failure started. Otherwise, null
####WindowsConnectionSetting
current Windows Connection Setting of this machine
####IsPreparing
current PvD State of this machine (currently only used for IsPreparing value)
####FaultState
current Fault State of this machine
####OSType
Broker name: OsType Desktop Director name: OS
####CurrentLoadIndex
Most recent Load index value of machine (null if no data)
####CurrentLoadIndexId
Foreign key associating this Machine record with the current LoadIndex record
####CatalogId
Foreign key associating this Machine record with a Catalog
####DesktopGroupId
Foreign key associating this Machine record with a DesktopGroup
####HypervisorId
Foreign key associating this Machine record with a Hypervisor
####Catalog
Catalog this machine was created from
####DesktopGroup
The group this desktop is part of
####Hypervisor
The hypervisor that this machine is associated with - can be null - not all machines are powered by hypervisors
####Sessions
List of past and present sessions for this Machine
####LoadIndex
LoadIndex associated with this machine
####MachineFailures
Failures associated with this machine
###Methods


####Constructor
Default constructor for machine object

##Monitor.Model.V1.Session
            
Represents a user connected to a desktop.
        
###Properties

####
unique identifier for DesktopGroupSummary
####
Timeslot to the minute that this summary data represents The summary date.
####
Foreign key associating this SessionActivitySummary record with a DesktopGroup
####
The desktop group this summary data represents The desktop group.
####
Number of maximum connected sessions for this desktop group for the minute specified The count of connected sessions.
####
Number of maximum disconnected sessions for this desktop group for the minute specified The count of disconnected sessions.
####
Number of maximum concurrent sessions for this desktop group for the minute specified The count of Concurrent sessions.
####
Total logon duration in milliseconds for all logons in this desktop group for the minute specified The average duration of the logon.
####
Total number of logons in this desktop group for the minute specified The total log on count.
####
Granularity of this summary item in minutes (how many minutes of data included in this record) The granularity.
####SessionKey
Broker assigned SessionKey for this Session
####StartDate
Time the session started (logon)
####LogOnDuration
Total log on duration for this session
####EndDate
Time the session ended (logoff)
####ExitCode
Session destroy exit code
####Failure
How the session failed (null if no failure) TODO: Populate when processing failure events
####FailureDate
If the connection failed, the time the failure occurred. Otherwise, null TODO: Populate when processing failure events
####ConnectionState
Connection State for the session
####ConnectionStateChangeDate
Date of last connection state change
####LifecycleState
Lifecycle state for the Session
####CurrentConnectionId
Foreign key associating this Session record with the Current Connection
####CurrentConnection
Current connection for this session - session can be disconnected, just as long as it is not replaced by a new one
####UserId
Foreign key associating this Session record with a User
####User
User connected to this session maps to Last Connection User in Desktop Director UI
####MachineId
Foreign key associating this Session record with a Machine
####Machine
Machine this user is connected to for this session
####Connections
Details associated with this session (each connection should have a record)
###Methods


####Constructor
Default constructor

##Monitor.Model.V1.User
            
Represents a user in the system
        
###Properties

####Id
unique identifier for User
####Sid
Security Identifier - a binary value set by the system when the user is created
####Upn
Broker name: AssociatedUserUpns DesktopDirector name: UserUpn User Principal Name - has two parts: the UPN prefix (the user account name) and the UPN suffix (a DNS domain name). The parts are joined together by the at sign (@) symbol to make the complete UPN.
####UserName
Username in the form of DOMAIN\UserName
####FullName
Full name of the user. TODO: Make sure this is populated when added to poll and other events.
####Domain
Domain for the user
####Sessions
List of past and present sessions for this User