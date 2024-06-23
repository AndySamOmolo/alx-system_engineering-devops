# Issue Summary
## Duration:
Start: June 21, 2024, 14:00 EAT
End: June 21, 2024, 15:00 EAT

## Impact:
Our uploading service was slow and thus some users were unable to post from their accounts. When the users attempted to post anything they saw a loading screen which did not stop until the uploading process was cancelled. ** 60% ** of the users were affected by the service slowdown.

## Root Cause:
The root cause of the issue was the uploading servers being overwhelmed by the high number of users uploading to them concurrently. This caused them to have a backlog of uploads which they were unable to process.

# Timeline
** 14:00 EAT ** - The issue is detected by a user who is unable to upload a post after 5 minutes of waiting.
** 14:02 EAT ** - The issue is reported to a customer care agent by the user through the customer care email.
** 14:05 EAT ** - Customer care assumed problem was on customers part due to the issue being reported by only one user.
** 14:10 EAT ** - Customer care told user to troubleshoot their network on their end through various troubleshooting options.
** 14:20 EAT ** - After a few more reports from other users with the same issue customer care forwarded issue to IT department.
** 14:30 EAT ** - The IT department was able to figure out the issue was the servers and started installing new ones.
** 14:45 EAT ** - The servers were successfully installed and issue was resolved after servers started operating.

# Root Cause and Resolution
The issue was caused by the servers being overwhelmed by the number of uploads they were required to process. Normally the servers would be able to handle a large number of concurrent uploads but the increase in the number of users in the past couple of days overwhelmed the servers since they lacked enough memory to process the upload requests. The IT department had already noticed the increasing number of users and had thus procured new servers. After installing the new servers the issue was resolved as the new servers could process the overload which was caused by the lack of memory. The new servers processed the backlog of uploads and increased the total memory of the servers thus enabling them to process a larger number of uploads than the previous server setup. This ensures that if there is ever another time a large number of users try to upload to the platform concurrently the servers will be able to handle it.

# Corrective and Preventative Measures
## Things to be improved:
- The IT department should always monitor the servers to check whether they are able to handle the load being sent to them at all times. They should also include an overhead in the servers incase the users increase.
- The customer care department should convey issues reported by users immediately to decrease service downtime.

## Tasks to be addressed:
- Add monitoring on server memory.
- Add overhead to the memory of the servers.
- Have extra servers on standby.
- Improve the issue reporting from customer care.
