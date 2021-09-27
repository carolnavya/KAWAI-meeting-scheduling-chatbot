## fallback
- utter_default

## greeting path 1
* greet
- utter_greet

## fine path 2
* fine_ask
- utter_reply

## create event path
*create_event
- utter_ofc
- action_create_event
- utter_confirm_created
- utter_anything_else

## list event path
*list_events
- utter_ofc
- action_list_events
- utter_confirm_list
- utter_anything_else

## delete event path
*delete_event
- utter_Ok_wait
- action_delete_event
- utter_confirm_delete
- utter_anything_else

## create event path
*update_event
- utter_ofc
- action_update_event
- utter_Ok_wait
- utter_confirm_updated
- utter_anything_else

## thanks path 1
* thanks
- utter_anything_else

## bye path 1
* bye
- utter_bye
