def cal_f1_score(tp, fp, fn):

    # This function is used to check whether the input tp, fp, fn is a interger and greater than zero or not.
    # If the inputs meet the required conditions, this function will calculate the f1_score

    if not isinstance(tp, int):
        print("tp must be int")
        return
    if not isinstance(fp, int):
        print("fp must be int")
        return
    if not isinstance(fn, int):
        print("fn must be int")
        return
    
    if tp <= 0 or fp <= 0 or fn <= 0:
        print("tp, fp, and fn must be greater than zero")
        return
    
    precision = tp / (tp + fp)
    recall = tp / (tp + fn)
    f1_score = 2 * (precision * recall) / (precision + recall)
    
    print(f'Precision is {precision}')
    print(f'Recall is {recall}')
    print(f'F1 Score is {f1_score}')
    return f1_score

#code for testing function operation
assert round (cal_f1_score ( tp =2 , fp =3 , fn =5) , 2) == 0.33
print (round (cal_f1_score ( tp =2 , fp =4 , fn =5) , 2))
