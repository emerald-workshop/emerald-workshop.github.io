<table style="width:100%">
    <tbody>
        <tr>
            <td><h4>LOCO: Building Applications in Network Memory with Cross-Node Objects</h4> <br> <b>George Hodgkins</b> <br> University of Colorado, Boulder and Sandia National Lab, US</td>
            <td width="150"><img src="Hodgkins.jpg" alt="George Hodgkins" height="150"/> </td>
        </tr>
        <tr>
            <td colspan=2>
            <button class="accordion">Show/hide abstract</button>
            <div class="panel">
              <p>In this talk, we explore the the idea of objects as a programming model for clusters using network memory (RDMA or CXL). We argue that the natural representation of an application designed for network memory is a system of interconnected objects which extend well-defined methods to the programmer, similar to traditional object-oriented application designs. These concurrent objects store their state in a distributed fashion across all participating nodes, especially in an incoherent or uncacheable memory network. In a sense, channel state is stored "across the network".</p>

                <p>Based on this philosophy, we introduce the Library of Channel Objects (LOCO), a shared-memory-like object-based library for RDMA and extensible to other weak memories. Channels are composable and reusable, and designed for both the strong locality effects and the weak consistency of RDMA.  Unlike prior work, LOCO channels do not hide memory complexity, instead relying on the programmer to use NUMA-like techniques to explicitly manage each object. As a consequence, our channel objects have performance similar to custom RDMA systems (e.g. distributed maps), but with a far simpler programming model. Our distributed map channel has better read and comparable write performance to a state-of-the-art custom RDMA solution, using well-encapsulated and reusable primitives.</p>
            </div>
            </td>
        </tr>
    </tbody>
</table>