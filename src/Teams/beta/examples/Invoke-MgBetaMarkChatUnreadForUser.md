### Example 1: Code snippet

```powershell

Import-Module Microsoft.Graph.Beta.Teams

$params = @{
	user = @{
		id = "d864e79f-a516-4d0f-9fee-0eeb4d61fdc2"
		tenantId = "2a690434-97d9-4eed-83a6-f5f13600199a"
	}
	lastMessageReadDateTime = [System.DateTime]::Parse("2021-05-27T22:13:01.577Z")
}

Invoke-MgBetaMarkChatUnreadForUser -ChatId $chatId -BodyParameter $params

```
This example shows how to use the Invoke-MgBetaMarkChatUnreadForUser Cmdlet.

