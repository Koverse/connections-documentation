
Models
------

Users can create Models to find and score the objects in the system. There are currently 3 types of Models that can be configured.

Model Types
+++++++++++

**Lookalike Models**

A Lookalike model is the simplest type of model. Lookalike models use an existing list as a training set and will score all the other objects based on how similar they are to the objects in the training set.

**Scoring Models**

A Scoring model scores objects based on a linear combination of user defined scores associated with a specific field value pair.

For example, a Scoring model might specify that having the field "Industry" with the value "Finance" increases an object's score by 50 and having the field "Deal Status" with a value of "Closed" will increase the score by 80. The result being that any object with both of those field/value pairs would have a final score of 130.

**Weighted Models**

A Weighted model is similar to a Scoring model because it also assigns a score to field/value pairs, but it goes one step further by allowing the user to limit the overall impact of individual fields.

Using the same example given above for Scoring models, the user could choose to limit the impact of the "Industry" field by assigning a weight of 30, and assigning a weight of 70 to the "Deal Status" field.

The weights applied to the fields must add up to 100.

Create a Model
++++++++++++++
To create a model, navigate to the Models page and click "CREATE MODEL":

1. Select the type of model you would like to create and click 'Next'
2. Follow the steps to configure your model. The steps will be different based on the model type that was selected.
3. Name your model. Koverse Connections will show the results of this model in various places throughout the tool so its helpful to name the model in such a way that it explains what its modeling for. For example, names starting with "Similar to Top Customers Last Year" is a good name.

4. Click "SAVE MODEL"

Your model will now appear on the Models page.

Run a Model
+++++++++++
To run a model, navigate to the Models page and click on the model you want to run.

On the detail page for the model, click on "RUN MODEL". You should see a green prompt in the lower left hand corner of your browser window telling you "Model has been queued". This model will then run based on your Koverse Connections system settings.


Model Options
+++++++++++++
From the Models page you can click on a model to access more details.

You can sort the models by clicking on the header column you want to sort by. You can also run a model from this page.

From the actions menu drop-down you can: rename, change the privacy settings, or delete a model.

On the details page of a model you can:

- View more information about the model including: Name, who created the model, and when the model was last run
- Make the model private or public using the "Public/Private" toggle
- Run the model
- Rename the model
- See the object results of the model
- Search across the data in the model
