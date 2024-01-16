# Hello warrior programmer

In this task, you have data that is in the file, assuming that you got it from the database, and you have to return it to the format of the following tasks for the following APIs, there is no need to write API or (function or class )set up the project.


### Steps

1. **Task One**: Imagine that you have an API to send a list of feedbacks and you need to return only the _required_ fields.
   **Note**: All objects that have an id must be sent to the format `(id, data) => {id: "id", data:{others}}` you need a function for sorting each array including `sortIndex`.

2. **Task Two**: Imagine that you have an API to send feedback based on ID, but you must return all existing fields.
   **Note**: All objects that have an id must be sent to the format (id, data) => {id: "id", data:{others}} you need a function for sorting each array including sortIndex.

3. **_(OPTIONAL)_** **Task Three**: In this address feedbacks[feedback][values][65a2575fd6a685e68963de13] is equal to this address feedbacks[inputs][id], imagine you need API for return only feedback from feedbacks that in the values field you must return concat data with inputs like:

```js
"65a2575fd6a685e68963de13": [
    "test"
]
```

\+

```json
{
  "id": "65a2575fd6a685e68963de13", //*
  "label": "در کدام شهر هستید؟", //*
  "formId": "65a25608d6a685e68963ddc3", //*
  "stepId": "65a25608d6a685e68963ddc5", //*
  "sectionId": "65a25608d6a685e68963ddc7", //*
  "sortIndex": 11, //*
  "placeholder": "شهر شما؟",
  "visibleAccordingTo": [],
  "isRequired": true, //*
  "isHidden": false,
  "isFullwidth": false,
  "type": "text", //*
  "minLength": 1,
  "maxLength": 360
}
```

=

```js
"65a2575fd6a685e68963de13": [
  {
      value: "test",
      "label": "در کدام شهر هستید؟",//*
      "formId": "65a25608d6a685e68963ddc3",//*
      "stepId": "65a25608d6a685e68963ddc5",//*
      "sectionId": "65a25608d6a685e68963ddc7",//*
      "sortIndex": 11,//*
      "placeholder": "شهر شما؟",
      "visibleAccordingTo": [],
      "isRequired": true,//*
      "isHidden": false,
      "isFullwidth": false,
      "type": "text",//*
      "minLength": 1,
      "maxLength": 360
  }
]
```

### Important Note

**Pay attention to the following:**
**Note that the \* sign means that this field is required**
1. Your final code should be in **a single file**.
2. Don't use any package to solve and just use JS possibilities like classes or functions as you like.
3. Pay attention to the naming.
4. Note that the score for solving the optional task is calculated only if exercises 1 and 2 have been solved.

**_GOOD LUCK_**
