Download Link: https://assignmentchef.com/product/solved-csc3002f-assignment3-memory-management
<br>
Write a Python program that implements the <em>FIFO</em>, <em>LRU</em>, and <em>optimal </em>page replacement algorithms presented in <em>Chapter 9: Virtual Memory </em>of Silberschatz et al. [Silberschatz et al., 2012].

First, generate a random page-reference string where page numbers range from 0 to 9. Apply the random page-reference string to each algorithm, and record the number of page faults incurred by each algorithm.

Implement the <em>FIFO</em>, <em>LRU</em>, and <em>optimal </em>(OPT) replacement algorithms so that the number of page frames can vary from 1 to 7. Assume that <em>demand paging </em>is used. The <em>main </em>function should include the following.:

def main(): #…TODO…

size = int(sys.argv[1]) print ’FIFO’, FIFO(size,pages), ’page faults.’ print ’LRU’, LRU(size,pages), ’page faults.’ print ’OPT’, OPT(size,pages), ’page faults.’

if __name__ == “__main__”:

if len(sys.argv) != 2:

print ’Usage: python paging.py [number of pages]’ else:

main()

1

Implement these FIFO, LRU and OPT algorithms as functions within one file called <em>paging.py</em>, making sure that you clearly identify yourself (name and student number) in comments at the top of the file.

The total assignment mark (100) will be calculated as follows.:

<ol>

 <li>Correct implementation and functioning of FIFO.</li>

 <li>Correct implementation and functioning of LRU.</li>

 <li>Correct implementation and functioning of OPT.</li>

</ol>

<strong>Note: </strong>Values in bold parentheses are the percentage weighting of each question as a portion of the total assignment mark.