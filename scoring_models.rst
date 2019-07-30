Scoring Models
---------------
A Scoring Model creates a list based on a weighted criteria model that represents a linear combination of attribute values (e.g. 0.2*assets + 0.8*performance)

.. image:: ../connections-documentation/scoring_model_landing.png

Create a Scoring Model
+++++++++++++++++++++++
To create a scoring model navigate to the Scoring Models tab and click "CREATE WEIGHTED MODEL". You will be asked to:

1. Name Your Scoring Model
  - Koverse Connections stores all scoring models in specific Scoring Models list, so there is no need to name it 'Scoring model of ...' Instead, try to give it a self explanatory and meaningful to you name.

  .. image:: ../connections-documentation/scoring_model_create_step1.png

2. Choose the object type your scoring model will run on

  .. image:: ../connections-documentation/scoring_model_create_step2.png

3. Choose the fields and values you would like to focus on for your new scoring model
  - If a field has more than one value, you may select one or multiple values. On the next page you will be able to individually score each value.

  .. image:: ../connections-documentation/scoring_model_create_step3.png

4. Assign scores to your chosen properties. These values will be used as multipliers for matching entities when determining their score.
  - Here you can assign scores to each chosen value from the Edit Properties step.
  - You can type in a score or use the slider to choose a score.
  - You can also delete a value that you no longer wish to give a score in your model.

  .. image:: ../connections-documentation/scoring_model_create_step4.png

  - Click "SAVE AND RUN MODEL"

Run a Scoring Model
++++++++++++++++++++
To run a scoring model, from the Scoring Models tab, click on the scoring model you want to run.

On the next page, click on "RUN MODEL". You should see a green prompt in the lower left hand corner of your browser window telling you "Model has been queued". This model will then run based on your Koverse Connectons system settings.

.. image:: ../connections-documentation/scoring_model_run.png
  :height: 50%
  :width: 50%

Scoring Model Options
++++++++++++++++++++++
From the Scoring Models tab you can click on a scoring model to access more details.

From the actions menu drop-down you can: rename a scoring model, make public or private a scoring model, copy a scoring model, edit a scoring model, or delete a scoring model.

.. image:: ../connections-documentation/scoring_model_actions1.png

On the details page of a scoring model you can:

- View more information about the scoring model including: Name, number of entities, who created the model, and when the model was last run
- Make the scoring model private or public using the "Public/Private" toggle
- Run the scoring model
- Rename the scoring model
- See the object results of the scoring model
- Search across the data in the scoring model

.. image:: ../connections-documentation/scoring_model_details.png
