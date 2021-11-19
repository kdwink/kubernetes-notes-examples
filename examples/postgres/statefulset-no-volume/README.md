Even in a stateful set the storage within a pod is NOT persistent, so this is not a good solution.

Database table would be lost on pod scale to zero or host restart.