# Blog-5

#### 4/28/23


### Context 

During the past few weeks I have been learning more about my tool JSON and utilize it. Since I am finished with my MVP as in my minimum valuable product, I am now attempting to connect a button from a survey that when clicked it would send out the information relay it back and then update the calendar with a new event. Currently  I have a few ways of how it would get to work but they havent for either missing a little part or being an overflow and moving to a new page.

### Process 

Through many experiments I have come up with a way to get a survey made with code then then try to take the responses and use it.

```
<script type="text/javascript">
    function submitform(){
        alert("Sending Json");
        var xhr = new XMLHttpRequest();
        xhr.open(form.method, form.action, true);
        xhr.setRequestHeader('Content-Type', 'application/json; charset=UTF-8');
        var j = {
            "first_name":"binchen",
            "last_name":"heris",
        };
        xhr.send(JSON.stringify(j));

```


All of these varibles all come together to take the form and then put it to a different place 

### Engeneering Design Process (EDP)

So far in my process I have made a working calendar that uses pre-input events to display them for different days that are chosen. I am trying to get the form or survey to make the responses go to the right place in order to go and then come back to put it into the calendar and show a new event.

### Skills 

Some of the skills that I have is good at understanding physics and the logic behind things of why something happens. So the differences between some forces, how they are affected and different parts that would be important depending on the task.





