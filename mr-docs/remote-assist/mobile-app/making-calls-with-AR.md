---
title: Making calls with AR in Dynamics 365 Remote Assist mobile
author: xonatia
description: Making calls from Dynamics 365 Remote Assist mobile with AR support 
ms.author: xolee
ms.date: 07/01/2020 
ms.service: crm-online
ms.topic: article
ms.reviewer: krbjoran
---
# Make Dynamics 365 Remote Assist mobile calls with augmented reality supported devices

Dynamics 365 Remote Assist mobile makes conducting repairs and remote inspections easy by providing technicians with the ability to launch one-to-one video calls with remote collaborators inside or outside of their organization. Making calls with Dynamics 365 Remote Assist mobile is available in these three scenarios:

1. A call between two Dynamics 365 Remote Assist mobile users
2. A call between a Dynamics 365 Remote Assist mobile user and a Teams desktop user
3. A call between a Dynamics 365 Remote Assist mobile user and a Teams mobile user

> [!NOTE]
> The following scenarios are **not** supported on Dynamics 365 Remote Assist mobile at this time:
>
> - Joining Teams meetings.
> - Making calls to browser-based Teams.
> - Participating in calls with three or more participants.
> - Participating in Dynamics 365 Remote Assist mobile to Dynamics 365 Remote Assist on HoloLens calls.

## Prerequisites

- In order to follow along with this guide, you must be using a mobile device with ARCore or ARKit support. Learn about Dynamics 365 Remote Assist's device [requirements](../requirements.md).
- Technicians must have a Dynamics 365 Remote Assist [free trial](../try-remote-assist.md) or [subscription](../buy-remote-assist.md).
- Remote collaborators must have a Dynamics 365 Remote Assist free trial or subscription and/or Microsoft Teams [free trial or subscription](https://www.microsoft.com/microsoft-365/microsoft-teams/group-chat-software). Learn to set up Dynamics 365 Remote Assist with [Teams desktop](../teams-pc-all.md) and [Teams mobile](../teams-mobile-all.md).

## How it works

1. Launch and sign into Dynamics 365 Remote Assist on your iOS or Android device.

2. Search for the remote collaborator's name.

![Screenshot of Dynamics 365 Remote Assist mobile, showing the contacts screen and highlighting the search icon.](./media/calls_2.png "Search")

3. Select the remote collaborator's name and launch a call.

  > [!NOTE]
  > If the remote collaborator is receiving the call on a mobile device with both Dynamics 365 Remote Assist mobile and Teams mobile installed, the remote collaborator can only answer on Teams mobile. Both users will have the same capabilities.

![Screenshot of Dynamics 365 Remote Assist mobile showing the Launch Call button.](./media/calls_3.png)

4. If the remote collaborator answers the call on **Dynamics 365 Remote Assist mobile**, the technician's live video feed will be shared to the remote collaborator's device screen.

![Screenshot of Dynamics 365 Remote Assist mobile to Dynamics 365 Remote Assist mobile call.](./media/ram-ram_toolbar.png)

If the remote collaborator answers the call on **Teams desktop**, the technician's live video feed will be shared to the remote collaborator's device screen.

![Screenshot of a Dynamics 365 Remote Assist mobile to Microsoft Teams call.](./media/ram-teams-video.png)

5. With the call controls toolbar, the technician can disable the video call (enter an audio-only call), mute themselves in call, turn on their speakers, or end the call. 

![Screenshot of the Dynamics 365 Remote Assist mobile toolbar, pointing at the video toggle icon, the mic toggle icon, the speaker toggle icon, and the end call icon.](./media/calltoolbar.png)

6. During the call, both call participants can place mixed reality annotations in the shared environment, capture and annotate snapshots, share files, record the call, and more!

## See also

- Learn how to make calls on Dynamics 365 Remote Assist mobile **without** ARCore or ARKit support [here](./calls-using-devices-without-ar.md).
- Learn how to place mixed reality annotations in the shared environment [here](./annotate-shared-environment.md).


[!INCLUDE[footer-include](../../includes/footer-banner.md)]