# QSAR
QSAR modeling to understand biological activity through the permeability of molecules.

####
In Cheminformatics, there is an in-silico process called QSAR that chemists use to make predictions about how different chemicals/compounds will interact with Cellular, environmental and molecular components. Some of these models work well and have been around for a while, but others are just simply wrong because model building is hard and they're always easy to mess up with the fancy computer programs that we use. While designing drugs and modeling the fate of chemicals, QSAR models play an important role. These models connect chemical properties to biological activity and are used by regulatory agencies in making decisions about safety assessments. There are two main types of QSAR model development: those that predict using regression analysis and those that use classification techniques.

The first and most important point to be noted here is that machines follow rules with efficiency, the very rules that we, the humans, set. So, the type of data we enter is the sole deciding factor for the outcome. But if you are not sure and enter values/ data with no proper relation or sequence, models will produce garbage even when it looks like things should be working fine. The application of this evolving technology has not only increased the efficiency but also enhanced the accuracy during various stages involved in drug discovery processes. This, therefore, has led to faster identification and development of novel drug candidates with higher therapeutic potential.

QSAR modeling has the following basic principles that are followed to validate a model:

a. Representation of Chemicals through 2D or 3D molecular descriptors.

b. Using statistical methods like Multiple Linear Regression MLR and stepwise Multiple Linear Regression MLR on the data set.

c. Validation of the model’s stability through external as well as internal methods of validation.

d. Validating the predictability of the model

e. Interpretation of the final descriptors selected after using the model

A typical QSAR equation is elaborated as a Linear Equation, where:

Biological Activity = Const + (C1 x P1) + (C2 x P2) + (C3 x P3) + ... + (Cn x Pn)

The descriptors of the molecules in the series are assigned parameters (P1-Pn) and coefficients (C1-Cn) and are based on their biological activity. Statistical techniques are used to derive a QSAR by analysing variations in these parameters [2]. QSAR, being a very sensitive modeling technique, depends on the quality of the data and the choice of descriptors (what descriptors are would be explained in a later chapter).

This is what the book caters.

There are several books about how to do QSAR modeling with rules and different attributes that one needs to consider, all the correct processes one should proceed to undertake to create a good model and then execute model validation through different statistical validation matrices, just like we have explained earlier.

This book does not do that. This book doesn’t speak of any of the ways a QSAR model should be created, validated and so on… This book speaks of all the mistakes one makes while going through the process. This book speaks of all the processes not to undertake while QSAR modeling, from the experience so far. Steps like Data Selection, Descriptor Selection, Scaffold Selection, Model selection and finally Model validation comprise the backbone of QSAR modeling and are the steps where recurrent errors happen, and that can completely change the outcome of on-going research.

We noticed that these mistakes are very hard to catch for beginners who are undertaking QSAR modeling; these mistakes are easily overlooked due to either a ‘perfect’ dataset or a ‘perfect’ score during validation. But what QSAR does is an in-depth analysis, where the aim needs to be very precise, that then slowly reveals the errors and problems after reviewing papers over and over again (we had to do the same 9 odd times). However, after finally locating the problem/s, the paper itself loses its value, completely It shatters the trust upon understanding and the computational process.

To stop this from happening, to save time and to point out all the signs that the paper or the model might have a problem we are dedicating this book to all the novices in this field.

This book is a negative aspect-based and opinion-based guide to QSAR Modeling with real-time example, of our failed paper and why it failed step by step., so that it can might come in handy to any newcomer in this field to look out for all the signs necessary.
