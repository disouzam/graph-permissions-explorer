# Chat.ReadWrite

> Allows an app to read and write 1 on 1 or group chats threads, on behalf of the signed-in user.
## Graph Methods

Type: A = Application Permission, D = Delegate Permission

|Ver|Type|Method|
|-------|----|------|
|V1|D|[DELETE /chats/{chat-id}/pinnedMessages/{pinnedChatMessageId}](https://docs.microsoft.com/graph/api/chat-delete-pinnedmessages?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /chats](https://docs.microsoft.com/graph/api/chat-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /chats/{chat-id}](https://docs.microsoft.com/graph/api/chat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /chats/{chat-id}/members](https://docs.microsoft.com/graph/api/chat-list-members?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /chats/{chat-id}/members/{membership-id}](https://docs.microsoft.com/graph/api/chat-get-members?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /chats/{chat-id}/messages](https://docs.microsoft.com/graph/api/chat-list-messages?view=graph-rest-1.0&tabs=http)|
|Beta|D|[GET /chats/{chat-id}/operations](https://docs.microsoft.com/graph/api/chat-list-operations?view=graph-rest-beta&tabs=http)|
|Beta|D|[GET /chats/{chat-id}/operations/{operation-id}](https://docs.microsoft.com/graph/api/teamsasyncoperation-get?view=graph-rest-beta&tabs=http)|
|V1|D|[GET /chats/{chat-id}/pinnedMessages](https://docs.microsoft.com/graph/api/chat-list-pinnedmessages?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /chats/{id}/members](https://docs.microsoft.com/graph/api/conversationmember-list?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/chats/{chat-id}](https://docs.microsoft.com/graph/api/chat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /me/chats/{chat-id}/messages](https://docs.microsoft.com/graph/api/chat-list-messages?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}](https://docs.microsoft.com/graph/api/chatmessage-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}/hostedContents](https://docs.microsoft.com/graph/api/chatmessage-list-hostedcontents?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}/hostedContents/{hosted-content-id}](https://docs.microsoft.com/graph/api/chatmessagehostedcontent-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}/replies/{reply-id}](https://docs.microsoft.com/graph/api/chatmessage-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}/replies/{reply-id}/hostedContents](https://docs.microsoft.com/graph/api/chatmessage-list-hostedcontents?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /teams/{team-id}/channels/{channel-id}/messages/{message-id}/replies/{reply-id}/hostedContents/{hosted-content-id}](https://docs.microsoft.com/graph/api/chatmessagehostedcontent-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id | user-principal-name}/chats/{chat-id}](https://docs.microsoft.com/graph/api/chat-get?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id | user-principal-name}/chats/{chat-id}/members](https://docs.microsoft.com/graph/api/chat-list-members?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id | user-principal-name}/chats/{chat-id}/members/{membership-id}](https://docs.microsoft.com/graph/api/chat-get-members?view=graph-rest-1.0&tabs=http)|
|V1|D|[GET /users/{user-id | user-principal-name}/chats/{chat-id}/messages](https://docs.microsoft.com/graph/api/chat-list-messages?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /chats/{chat-id}](https://docs.microsoft.com/graph/api/chat-patch?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /teams/(team-id)/channels/{channel-id}/messages/{message-id}](https://docs.microsoft.com/graph/api/chatmessage-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[PATCH /teams/(team-id)/channels/{channel-id}/messages/{message-id}/replies/{reply-id}](https://docs.microsoft.com/graph/api/chatmessage-update?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /chats](https://docs.microsoft.com/graph/api/chat-post?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /chats/{chat-id}/markChatReadForUser](https://docs.microsoft.com/graph/api/chat-markchatreadforuser?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /chats/{chat-id}/markChatUnreadForUser](https://docs.microsoft.com/graph/api/chat-markchatunreadforuser?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /chats/{chat-id}/members](https://docs.microsoft.com/graph/api/chat-post-members?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /chats/{chat-id}/messages](https://docs.microsoft.com/graph/api/chat-post-messages?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /chats/{chat-Id}/pinnedMessages](https://docs.microsoft.com/graph/api/chat-post-pinnedmessages?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /chats/{chatsId}/hideForUser](https://docs.microsoft.com/graph/api/chat-hideforuser?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /chats/{chatsId}/unhideForUser](https://docs.microsoft.com/graph/api/chat-unhideforuser?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamId}/channels/{channelId}/messages/{messageId}/replies/{replyId}/setReaction](https://docs.microsoft.com/graph/api/chatmessage-setreaction?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamId}/channels/{channelId}/messages/{messageId}/replies/{replyId}/softDelete](https://docs.microsoft.com/graph/api/chatmessage-softdelete?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamId}/channels/{channelId}/messages/{messageId}/replies/{replyId}/undoSoftDelete](https://docs.microsoft.com/graph/api/chatmessage-undosoftdelete?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamId}/channels/{channelId}/messages/{messageId}/replies/{replyId}/unsetReaction](https://docs.microsoft.com/graph/api/chatmessage-unsetreaction?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamsId}/channels/{channelId}/messages/{chatMessageId}/setReaction](https://docs.microsoft.com/graph/api/chatmessage-setreaction?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamsId}/channels/{channelId}/messages/{chatMessageId}/softDelete](https://docs.microsoft.com/graph/api/chatmessage-softdelete?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamsId}/channels/{channelId}/messages/{chatMessageId}/undoSoftDelete](https://docs.microsoft.com/graph/api/chatmessage-undosoftdelete?view=graph-rest-1.0&tabs=http)|
|V1|D|[POST /teams/{teamsId}/channels/{channelId}/messages/{chatMessageId}/unsetReaction](https://docs.microsoft.com/graph/api/chatmessage-unsetreaction?view=graph-rest-1.0&tabs=http)|
## Delegate Permission
|||
|-|-|
|**Id**|9ff7295e-131b-4d94-90e1-69fde507ac11|
|**Consent Type**|User|
|**Display String**|Read and write user chat messages|
|**Description**|Allows an app to read and write 1 on 1 or group chats threads, on behalf of the signed-in user.|
## Resources
### [change-notifications-api-overview](https://docs.microsoft.com/graph/api/resources/change-notifications-api-overview?view=graph-rest-1.0&tabs=http)

### [channel ](https://docs.microsoft.com/graph/api/resources/channel?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|createdDateTime|dateTimeOffset|Read only. Timestamp at which the channel was created.|
|description|String|Optional textual description for the channel.|
|displayName|String|Channel name as it will appear to the user in Microsoft Teams. The maximum length is 50 characters.|
|email|String| The email address for sending messages to the channel. Read-only.|
|id|String|The channel's unique identifier. Read-only.|
|isArchived| Boolean | Indicates whether the channel is archived. Read-only. |
|isFavoriteByDefault|Boolean|Indicates whether the channel should be marked as recommended for all members of the team to show in their channel list. **Note:** All recommended channels automatically show in the channels list for education and frontline worker users. The property can only be set programmatically via the Create team method. The default value is `false`.|
|membershipType|channelMembershipType|The type of the channel. Can be set during creation and can't be changed. The possible values are: `standard`, `private`, `unknownFutureValue`, `shared`. The default value is `standard`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value in this evolvable enum: `shared`.|
|tenantId |string | The ID of the Microsoft Entra tenant. |
|webUrl|String|A hyperlink that will go to the channel in Microsoft Teams. This is the URL that you get when you right-click a channel in Microsoft Teams and select Get link to channel. This URL should be treated as an opaque blob, and not parsed. Read-only.|
|summary|channelSummary|Contains summary information about the channel, including number of owners, members, guests, and an indicator for members from other tenants. The **s
### [chat ](https://docs.microsoft.com/graph/api/resources/chat?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
| chatType| chatType | Specifies the type of chat. Possible values are: `group`, `oneOnOne`, `meeting`, `unknownFutureValue`.|
| createdDateTime| dateTimeOffset|  Date and time at which the chat was created. Read-only.|
| id| String| The chat's unique identifier. Read-only.|
| lastUpdatedDateTime| dateTimeOffset|  Date and time at which the chat was renamed or the list of members was last changed. Read-only.|
| onlineMeetingInfo | teamworkOnlineMeetingInfo | Represents details about an online meeting. If the chat isn't associated with an online meeting, the property is empty. Read-only.|
| tenantId| String | The identifier of the tenant in which the chat was created. Read-only.|
| topic| String|  (Optional) Subject or topic for the chat. Only available for group chats.|
| viewpoint|chatViewpoint|Represents caller-specific information about the chat, such as the last message read date and time. This property is populated only when the request is made in a delegated context.|
| webUrl | String| The URL for the chat in Microsoft Teams. The URL should be treated as an opaque blob, and not parsed. Read-only. |
### [chatMessage ](https://docs.microsoft.com/graph/api/resources/chatmessage?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|attachments|chatMessageAttachment collection |References to attached objects like files, tabs, meetings etc.|
|body|itemBody|Plaintext/HTML representation of the content of the chat message. Representation is specified by the contentType inside the body. The content is always in HTML if the chat message contains a chatMessageMention. |
|chatId|string|If the message was sent in a chat, represents the identity of the chat.|
|channelIdentity|channelIdentity|If the message was sent in a channel, represents identity of the channel.|
|createdDateTime|dateTimeOffset|Timestamp of when the chat message was created.|
|deletedDateTime|dateTimeOffset|Read only. Timestamp at which the chat message was deleted, or null if not deleted. |
|etag| string | Read-only. Version number of the chat message. |
|eventDetail|eventMessageDetail|Read-only. If present, represents details of an event that happened in a **chat**, a **channel**, or a **team**, for example, adding new members. For event messages, the **messageType** property will be set to `systemEventMessage`.|
|from|chatMessageFromIdentitySet| Details of the sender of the chat message. Can only be set during migration.|
|id|String| Read-only. Unique ID of the message. IDs are unique within a chat/channel/reply-to-message, but might be duplicated in other chats/channels/reply-to-messages. |
|importance|string | The importance of the chat message. The possible values are: `normal`, `high`, `urgent`.|
|lastModifiedDateTime|dateTimeOffset|Read only. Timestamp when the chat message is created (initial setting) or modified, including when a reaction is added or removed. |
|lastEditedDateTime|dateTimeOffset|Read only. Timestamp when edits to the chat message were made. Triggers an "Edited" flag in the Teams UI. If no edits are made the value is `null`.|
|locale|string|Locale of the chat message set by the client. Always set to `en-us`.|
|mentions|chatMessageMention collection| List of entities mentioned in the chat message. Supported entities are: user, bot, team, and channel.|
|messageHistory|chatMessageHistoryItem collection|List of activity history of a message item, including modification time and actions, such as reactionAdded, reactionRemoved, or reaction changes, on the message.
|messageType|chatMessageType|The type of chat message. The possible values are: `message`, `chatEvent`, `typing`, `unknownFutureValue`, `systemEventMessage`. Note that you must use the `Prefer: include-unknown-enum-members` request header to get the following value in this evolvable enum: `systemEventMessage`.|
|policyViolation | chatMessagePolicyViolation |Defines the properties of a policy violation set by a data loss prevention (DLP) application.|
|reactions| chatMessageReaction collection | Reactions for this chat message (for example, Like).|
|replyToId| string | Read-only. ID of the parent chat message or root chat message of the thread. (Only applies to chat messages in channels, not chats.) |
|subject|string| The subject of the chat message, in plaintext.|
|summary|string| Summary text of the chat message that could be used for push notifications and summary views or fall back views. Only applies to channel chat messages, not chat messages in a chat. |
|webUrl|string|Read-only. Link to the message in Microsoft Teams.|
### [chatMessageHostedContent ](https://docs.microsoft.com/graph/api/resources/chatmessagehostedcontent?view=graph-rest-1.0&tabs=http)
| Property     | Type        | Description |
|:-------------|:------------|:------------|
|contentBytes  |Edm.Binary   | Write-only. When posting new chat message hosted content, represents the bytes of the payload and are represented as a base64 encoded string.|
|contentType   |String       | Write-only. When posting new chat message hosted content, represents the type of content, such as image/png.|
|id            |String       | Read-only. Represents the chat message hosted content identifier.|
### [conversationMember ](https://docs.microsoft.com/graph/api/resources/conversationmember?view=graph-rest-1.0&tabs=http)
| Property   | Type |Description|
|:---------------|:--------|:----------|
|displayName| string | The display name of the user. |
|id|String| Read-only. Unique ID of the user.|
|roles| string collection | The roles for that user. This property contains additional qualifiers only when relevant - for example, if the member has `owner` privileges, the **roles** property contains `owner` as one of the values. Similarly, if the member is an in-tenant guest, the **roles** property contains `guest` as one of the values. A basic member should not have any values specified in the **roles** property. An Out-of-tenant external member is assigned the `owner` role.|
|visibleHistoryStartDateTime| DateTimeOffset | The timestamp denoting how far back a conversation's history is shared with the conversation member. This property is settable only for members of a chat. |
### [pinnedChatMessageInfo ](https://docs.microsoft.com/graph/api/resources/pinnedchatmessageinfo?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
| id| String| The ID of the chatMessage. Read-only. |
### [team ](https://docs.microsoft.com/graph/api/resources/team?view=graph-rest-1.0&tabs=http)
| Property | Type | Description |
|:---------------|:--------|:----------|
| id | string | The unique identifier of the team. The group has the same ID as the team. This property is read-only, and is inherited from the base entity type. |
|classification|string| An optional label. Typically describes the data or business sensitivity of the team. Must match one of a pre-configured set in the tenant's directory. |
|classSettings|teamClassSettings |Configure settings of a class. Available only when the team represents a class.|
|createdDateTime|dateTimeOffset|Timestamp at which the team was created.|
|description|string| An optional description for the team. Maximum length: 1024 characters. |
|displayName|string| The name of the team. |
|funSettings|teamFunSettings |Settings to configure use of Giphy, memes, and stickers in the team.|
|guestSettings|teamGuestSettings |Settings to configure whether guests can create, update, or delete channels in the team.|
|internalId | string | A unique ID for the team that has been used in a few places such as the audit log/Office 365 Management Activity API. |
|isArchived|Boolean|Whether this team is in read-only mode. |
|memberSettings|teamMemberSettings |Settings to configure whether members can perform certain actions, for example, create channels and add bots, in the team.|
|messagingSettings|teamMessagingSettings |Settings to configure messaging and mentions in the team.|
|specialization|teamSpecialization| Optional. Indicates whether the team is intended for a particular use case.  Each team specialization has access to unique behaviors and experiences targeted to its use case. |
|summary|teamSummary| Contains summary information about the team, including number of owners, members, and guests. |
|tenantId |string | The ID of the Microsoft Entra tenant. |
|visibility|teamVisibilityType| The visibility of the group and team. Defaults to Public. |
|webUrl|string (readonly) | A hyperlink that will go to the team in the Microsoft Teams client. This is the URL that you get when you right-click a team in the Microsoft Teams client and select **G
### [teamsApp ](https://docs.microsoft.com/graph/api/resources/teamsapp?view=graph-rest-1.0&tabs=http)
| Property            | Type     | Description |
|:------------------- |:-------- |:----------- |
| displayName                | string   | The name of the catalog app provided by the app developer in the Microsoft Teams zip app package. |
| distributionMethod  | teamsAppDistributionMethod     | The method of distribution for the app. Read-only.|
| externalId          | string   | The ID of the catalog provided by the app developer in the Microsoft Teams zip app package. |
| id                  | string   | The app ID generated for the catalog is different from the developer-provided ID found within the Microsoft Teams zip app package. The **e
### [teamsAsyncOperation ](https://docs.microsoft.com/graph/api/resources/teamsasyncoperation?view=graph-rest-1.0&tabs=http)
| Property | Type	| Description |
|:---------------|:--------|:----------|
|attemptsCount|Int32|Number of times the operation was attempted before being marked successful or failed.|
|createdDateTime|DateTimeOffset |Time when the operation was created.|
|error|operationError|Any error that causes the async operation to fail.|
|id|string |Unique operation ID.|
|lastActionDateTime|DateTimeOffset |Time when the async operation was last updated.|
|operationType|teamsAsyncOperationType |Denotes the type of operation described. Possible values are: `invalid`, `cloneTeam`, `archiveTeam`, `unarchiveTeam`, `createTeam`, `unknownFutureValue`, `teamifyGroup`, `createChannel`, `archiveChannel`, `unarchiveChannel`. You must use the `Prefer: include-unknown-enum-members` request header to get the following values in this evolvable enum: `teamifyGroup`, `createChannel`, `archiveChannel`, `unarchiveChannel`. |
|status|teamsAsyncOperationStatus| Operation status.|
|targetResourceId|String |The ID of the object that's created or modified as result of this async operation, typically a team.|
|targetResourceLocation|string|The location of the object that's created or modified as result of this async operation. This URL should be treated as an opaque value and not parsed into its component paths.|
### [teamworkUserIdentity ](https://docs.microsoft.com/graph/api/resources/teamworkuseridentity?view=graph-rest-1.0&tabs=http)
|Property|Type|Description|
|:---|:---|:---|
|displayName|String|Inherited from identity. Display name of the user. Optional.|
|id|String|Inherited from identity. ID of the user. |
|userIdentityType|teamworkUserIdentityType| Type of user. Possible values are: `aadUser`, `onPremiseAadUser`, `anonymousGuest`, `federatedUser`, `personalMicrosoftAccountUser`, `skypeUser`, `phoneUser`, `unknownFutureValue` and `emailUser`.|
|tenantId|String|Identifier of tenant, which user is part of. Optional. |