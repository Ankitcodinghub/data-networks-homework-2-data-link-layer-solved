# data-networks-homework-2-data-link-layer-solved
**TO GET THIS SOLUTION VISIT:** [Data Networks Homework #2-Data Link Layer Solved](https://www.ankitcodinghub.com/product/data-networks-data-communication-networks-hw2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112796&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Data Networks  Homework #2-Data Link Layer Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Data Link Layer

Data Link Layer deals with the algorithms required to achieve reliable, efficient peer to peer communication using the physical layer. These algorithms are designed to provide appropriate services to the network layer such as acknowledged connection oriented services. Several algorithms can be used to provide such a service and the objective of this exercise is to study the concepts of these algorithms.

1. What services are provided by the data link layer for the network layer?

Unrestricted Simplex

The data link layer at the sender site gets data from its network layer, makes a frame out of the data, and sends it. The data link layer at the receiver site receives a frame from its physical layer, extracts data from the frame, and delivers the data to its network layer.

Stop and Wait Simplex

Sender send one data packet at a time and send next packet only after receiving acknowledgement for previous. Receiver send acknowledgement after receiving and consuming of data packet. After consuming packet acknowledgement need to be sent.

Stop and Wait

Sender sends one frame at a time. After sending each frame, the sender doesn’t send any further frames until it receives an acknowledgement (ACK) signal. The timeout countdown is reset after each frame transmission. Receiver after receiving a valid frame, the receiver sends an ACK. If the ACK does not reach the sender before a certain time, known as the timeout, the sender sends the same frame again.

1. Why a timer is used in the transmitter?

2. What is the main draw-back of this protocol and in what condition it is suitable to use it?

3. Is sequence number necessary for the transmitter’s packets and how many bits are sufficient for the sequence number? what about the Ack packets?

Go Back-N

The sending process continues to send a number of frames specified by a window size even without receiving an acknowledgement (ACK) packet from the receiver. It is a special case of the general sliding window protocol with the transmit window size of N and receive window size of 1. It can transmit N frames to the peer before requiring an ACK. The receiver process keeps track of the sequence number of the next frame it expects to receive, and sends that number with every ACK it sends.

1. What is the main draw-back of this protocol? What protocol solves this problem and how?

2. How many bits are sufficient for the sequence number and why?

Selective Repeat

Simulate the above mentioned protocols in Matlab.

Consider a noisy channel with Ploss, propagation delay Tp, packet transmission time Tt and a sender with window size of W. Change each parameter holding all others constant and compare efficiency (ratio of ideal to total number of transmissions) and time delay between Stop and Wait, Go Back-N and Selective Repeat protocols. Explain your results.

What SHOULD I prepare?

You must upload a report in Portable Document Format (.pdf) for this assignment. The document should contain answer to each question, any necessary comments and screen-shot of what you have done in each part. After this homework you must be familiar with elementary data link layer protocols and their characteristics.
