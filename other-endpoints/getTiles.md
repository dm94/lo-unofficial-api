
GET
https://myrealm.lastoasis.gg/realm/{REALM_ID}/map/indexdata

Response:


{
  "realmId": {REALM_ID},
  "tileList": [
    {
      "id": {TILE_ID},
      "name": "mods",
      "status": 2,
      "pendingStatus": null,
      "type": 0,
      "pvpMode": 0,
      "quality": 3,
      "map": {
        "id": {MAP_ID},
        "name": "Canyon",
        "difficulty": 1
      },
      "gameServer": null,
      "canActivate": false,
      "canDeactivate": false,
      "canDelete": false,
      "canUseAutomation": false,
      "isActive": true,
      "isInactive": false,
      "isPendingActive": false,
      "isPendingInactive": false,
      "isPendingDelete": false,
      "statusCssClass": "table-warning",
      "statusText": "Active",
      "hostingStatusText": "No game server available for hosting",
      "mapDifficultyCssClass": "bg-warning",
      "activationDate": null,
      "deactivationDate": null,
      "mapDifficultyText": "MEDIUM",
      "typeText": "Oasis",
      "pvpModeText": "Full PvP",
      "x": 8,
      "y": 5,
      "playerCount": 0
    }
  ],
  "canAddTile": true
}