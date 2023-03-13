# mama-fuas-allocation

import random

# List of casual laborers
casual_laborers = ['kennah', 'Johnte', 'wangare', 'faithr', 'Jane', 'kelsie', 'sandra', 'donald']

# allocate job to a casual laborer
def allocate_job():
    return random.choice(casual_laborers)

# Main 
if __name__ == '__main__':
    # Allocate job to a casual laborer
    allocated_laborer = allocate_job()
    print(f"Job allocated to {allocated_laborer}")
