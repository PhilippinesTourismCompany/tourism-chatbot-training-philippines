
TOURISM CHATBOTS PHILIPPINES 
DESIGN AND NOTATIONS 


## BOT 01 - ROUTING 

	BOT: 
	CLIENT: 


	BOT: 
	CLIENT: 

# OUTPUT 01: 
 text: 			"Please"
 call_to_action: PURCHASE 

### FACEBOOK ANALYTICS 

/**
 * This function will log AchievedLevel App Event
 * @param {string} level
 */
function logAchievedLevelEvent(level) {
    var params = {};
    params[FB.AppEvents.ParameterNames.LEVEL] = level;
    FB.AppEvents.logEvent(FB.AppEvents.EventNames.ACHIEVED_LEVEL, null, params);
}
