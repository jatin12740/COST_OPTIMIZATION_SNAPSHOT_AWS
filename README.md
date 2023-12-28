# COST_OPTIMIZATION_SNAPSHOT_AWS
The Lambda function efficiently manages EBS snapshots. By querying all EBS snapshots owned by the account, Upon identifying stale snapshots those no longer associated with active instance the Lambda function takes proactive measures to optimize storage costs by promptly deleting them.
