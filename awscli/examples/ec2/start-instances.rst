**To start an Amazon EC2 instance**

This example starts a instance with the instance ID ``i-1a2b3c4d``.

Command::

  aws ec2 start-instances --instance-ids i-1a2b3c4d

Output::

    {
        "StartingInstances": [
            {
                "InstanceId": "i-1a2b3c4d",
                "CurrentState": {
                    "Code": 0,
                    "Name": "pending"
                },
                "PreviousState": {
                    "Code": 80,
                    "Name": "stopped"
                }
            }
        ]
    }

For more information, see `Stop and Start Your Instance`_ in the *Amazon Elastic Compute Cloud User Guide*.

.. _`Stop and Start Your Instance`: http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/Stop_Start.html

