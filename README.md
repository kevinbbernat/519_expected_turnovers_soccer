# 519_expected_turnovers_soccer
519 Applied Machine Learning Project: Expected Turnovers in Soccer by Kevin Bernat, Alton Wiggers, and Ruifan Wang

Report Link: https://sites.google.com/seas.upenn.edu/fall21-cis519/#h.50tgfro4hg44

Abstract:

For this project, we focused on “turnovers” in soccer and explored expected goals in basketball

More specifically, we looked at individual moments in these sports and tried to use machine
learning to determine whether the individual play would result in one team giving over
possession of the ball to the other. This is important in sports for seeing how risky a team is
being on offense if they are giving up higher than expected turnovers and seeing how accurately
that risk can be assessed using machine learning. Our primary target contribution is to featurize
existing data to accommodate for the notion of turnovers, as it was not an inherent feature of
any dataset we were able to find. Then, using a collection of methods, we found how well
turnovers can be expected using machine learning. We found that XGBoost was able to perform
the best on this problem, although the feature set may still be too small for practical application
on real world games.