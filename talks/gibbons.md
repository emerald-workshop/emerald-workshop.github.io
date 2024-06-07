<table style="width:100%">
    <tbody>
        <tr>
            <td><h4>
Processing-in-Memory: Theory and Practice
            </h4> <br> <b>
Phillip Gibbons
            </b> <br> 
        Carnegie Mellon University, US
            </td>
            <td width="150"><img src="gibbons.jpeg" alt="Speaker's photo" height="150"/> </td>
        </tr>
        <tr>
            <td colspan=2>
            <button class="accordion">Show/hide abstract</button>
            <div class="panel">

            <p>As computational resources become more efficient and data sizes grow, data movement is fast becoming the dominant cost in computing.  Processing-in-Memory (a.k.a., near-data-processing), an idea dating back to at least 1970, is now emerging as a key technique for reducing costly data movement, by enabling computation to be executed on compute resources embedded in memory modules.  While there has been considerable recent work on the systems/architecture/technology side of PIM, there has been very little work addressing the theory/programming/algorithm side. Open problems include: How does/should programming/algorithm design on PIM systems differ from traditional shared/distributed settings?  What are the fundamental limitations/trade-offs in using PIM?</p>
<p>
This talk highlights our results-to-date addressing these questions.  As a driving application kernel, we focus on a novel PIM-friendly index structure supporting batch parallel inserts/deletes, point queries, and range queries.  Our index addresses head-on the inherent tension between minimizing communication and achieving load balance in PIM systems. We also summarize our results for other types of indexes and for database systems more generally. Finally, the talk will report on our experiences implementing our ideas on UPMEM’s 2,560-module PIM system.</p>
            </div>
            </td>
        </tr>
    </tbody>
</table>