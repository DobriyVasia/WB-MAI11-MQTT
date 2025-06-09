```json
[
	{
		"manufacturer": "WirenBoard",
		"model": "WB-MAI",
		"modelId": "/devices/(wb-mai11_[0-9]{1,3})/controls/(IN [0-9]{1,2}.?[PN]* Temperature)/meta/type",
		"catalogId": 76,
		"services": [
			{
				"name": "Температура",
				"type": "TemperatureSensor",
				"characteristics": [
					{
						"type": "CurrentTemperature",
						"link": {
							"type": "Float",
							"topicGet": "/devices/(1)/controls/(2)",
							"minStep": 0.1,
							"checkValue": true
						}
					}
				]
			}
		]
	},
	{
		"manufacturer": "WirenBoard",
		"model": "WB-MAI",
		"modelId": "/devices/(wb-mai11_[0-9]{1,3})/controls/(IN [0-9]{1,2}.?[PN]* Value)/meta/type",
		"catalogId": 76,
		"services": [
			{
				"name": "Датчики давления",
				"type": "HumiditySensor",
				"characteristics": [
					{
						"type": "CurrentRelativeHumidity",
						"link": {
							"type": "Float",
							"topicGet": "/devices/(1)/controls/(2)"
						}
					}
				]
			}
		]
	}
]
```
