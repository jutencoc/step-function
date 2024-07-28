### step-function
create a step function

# lambda code 
# for first lambda function
import json

def lambda_handler(event, context):
    # TODO implement
    print(event)
    print(len(event['accountNo']))
    x=len(event['accountNo'])
    if x == 8:
        return {
        "statusCode": 200    
        }
    else:
        return {
        "statusCode": 400
                    }



# for 1 lambda functio
# # for 3nd lambda functio


create step function 

add lambda function for first execution

add choise

add one lambda to left on to right

addd input code and execute 
