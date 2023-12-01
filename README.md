# ML_PROJECT_SPAM_CLASSIFICATION
spam classification project

This is a spam classifier that uses naive Bayesian probability. I created it as a proof of concept spam filter for a college course.

The classifier first takes a body of known spam and ham (non-spam) emails to evaluate. Then, it evaluates each email in a test body of emails as spam or ham, with the difference between ham and spam only known to the classifier for the purpose of calculating the success rate.

Several parameters can be changed to optimize the effectiveness of the classifier. By tweaking these parameters, rates in the upper 90% range for both spam and ham classification can be reached.

Included is a sample of Apache SpamAssassin’s public corpus of spam and ham emails for testing. I've also included the paper I wrote and the presentation I created for the project. These both detail the implementation details of the naive Bayesian probabilistic approach to spam filtering and its effectiveness.
