## [Shuuji Kajita](http://humanoids2017.loria.fr/conference-program/keynotes/)

in his talk "Title: The long and winding history of biped robot research",
Kajita surprised all the audience of humanoids when he signed
"The long and winding Road by the Beatles".

On the day of his talk Friday 17 November 2017, Boston Dynamics released a
[VIDEO](https://www.youtube.com/watch?v=fRj34o4hN4I) about the update of ATLAS
humanoid which "can now jump across
gaps, jump and spin 180°, and – most impressive of all – it can backflip,
even using its arms to balance after landing just like a
real gymnast [ [ref]](https://www.youtube.com/watch?v=WcbGRBPkrps)".

With that in mind, you can now imagine the feelings among the audience of
humanoids which were essentially amusement for such accomplishment
but at the same time demoralised for which reason Kajita in a way of advising
PhD students and junior researchers he mentioned of having the same
frustrated and demoralised experience when
HONDA released his latest update of his humanoid robot while he was
working in a slight simple version of a bided humanoid during his PhD [VID20171117103200].



## "Robots Learning from Robots: A Proof of Concept Study for Co-Manipulation Tasks"
Peternel, Luka	Istituto Italiano Di Tecnologia  
Ajoudani, Arash	Istituto Italiano Di Tecnologia  
[PAPER](https://www.researchgate.net/publication/320564082_Robots_Learning_from_Robots_A_Proof_of_Concept_Study_for_Co-Manipulation_Tasks)
[VIDEO: A Proof of Concept Study for Co-Manipulation Tasks](https://www.youtube.com/watch?v=AzK5ff0BO68)

In this paper we study the concept of robots learning from collaboration with skilled robots. The advantage of this concept is that the human involvement is reduced, while the skill can be propagated faster among the robots performing similar collaborative tasks or the ones being executed in hostile environments. The expert robot initially obtains the skill through the observation of and physical collaboration with the human. We present a novel approach to how a novice robot can learn the specifics of the co-manipulation task from the physical interaction with an expert robot. The method consists of a multi-stage learning process that can gradually learn the appropriate motion and impedance behaviour under given task conditions. The trajectories are encoded with Dynamical Movement Primitives and learnt by Locally Weighted Regression, while their phase is estimated by adaptive oscillators. The learnt trajectories are replicated by a hybrid force/impedance controller. To validate the proposed approach we performed experiments on two robots learning and executing a challenging co-manipulation task.




## "Human-Robot Interaction Assessment Using Dynamic Engagement Profiles"
Poltorak, Nicole	Univ. of Southern Denmark, https://www.ini.uzh.ch/people/poltorak
Drimus, Alin	Univ. of Southern Denmark
Keywords: Social interaction and acceptability, Visual perception, Cognitive development
Abstract: This paper addresses the use of convolutional neural networks for image
analysis resulting in an engagement metric that can be used to assess the quality
of human robot interactions. We propose a method based on a pretrained
convolutional network able to map emotions onto a continuous [0-1] interval,
where 0 represents disengaged and 1 fully engaged. The network shows a good
accuracy at recognizing the engagement state of humans given positive emotions.
A time based analysis of interaction experiments between small humanoid robots
and humans provides time series of engagement estimates, which are further used
to understand the nature of the interaction as well as the overall mood and
interest of the participant during the experiment. The method allows a
real-time implementation and supports a quantitative and qualitative assessment
of a human robot interaction with respect to a positive engagement and is
applicable to humanoid robotics as well as other related contexts.


## "Learning Inverse Dynamics Models in O(n) Time with LSTM Networks"
Rueckert, Elmar	Tech. Univ. Darmstadt
Nakatenus, Moritz	Tech. Univ. Darmstadt
Tosatto, Samuele	Tech. Univ. Darmstadt
Peters, Jan	Tech. Univ. Darmstadt
Keywords: Sensorimotor learning, Grasping and Manipulation, Learning from demonstration
Abstract: Inverse dynamics model learning is crucial for modern robots where
analytic models cannot capture the complex dynamics of compliant actuators,
elasticities, mechanical inaccuracies, frictional effects or sensor noise.
However, such models are highly nonlinear and millions of samples are needed to
encode a large number of motor skills. Thus, current state of the art model
learning approaches like Gaussian Processes which scale exponentially with the
data cannot be applied. In this work, we developed an inverse dynamics model
learning approach based on a long-short-term-memory (LSTM) network with a
time complexity of O(n). We evaluated the approach on a KUKA robot arm that was
used in object manipulation skills with various loads. In a comparison to
Gaussian Processes we show that LSTM networks achieve better prediction
performances and that they can be trained on large datasets with more than
100,000 samples in a few seconds. Moreover, due to the small training batch
size of for example 128 samples, the network can be continuously improved
in life-long learning scenarios.
