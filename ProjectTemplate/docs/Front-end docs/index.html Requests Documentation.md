= Index.html current Posting status 

== Code 

.jQuery Ajax Post Method
[source,javascript]
====
$.ajax({
				type: "POST", // Send data
				url: webMethod, //
				data: parameters,
				contentType: "application/json; charset=utf-8", 
				dataType: "json",
				success: function (msg) {
					var responseFromServer = msg.d;

					for (var i = 0; i < responseFromServer.length; i++) {
						alert(responseFromServer[i].firstName);
						alert(responseFromServer[i].lastName);
						alert(responseFromServer[i].phoneNumber);
					}
					
					doThisAfterServerStuff();
				},
				error: function (e) {
					alert("this code will only execute if javascript is unable to access the webservice");
				}
			});
====
