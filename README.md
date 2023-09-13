Candidate Elimination Algorithm

Algorithm:

Step1: Load Data set

Step2: Initialize General Hypothesis  and Specific  Hypothesis.

Step3: For each training example  

Step4: If example is positive example  
          if attribute_value == hypothesis_value:
             Do nothing  
          else:
             replace attribute value with '?' (Basically generalizing it)
             
Step5: If example is Negative example  
          Make generalize hypothesis more specific.

Q.1) Implement this candidate elimination algorithm using python programming to list out the consistent candidates of the training dataset.

" Note: Take your own training examples "
