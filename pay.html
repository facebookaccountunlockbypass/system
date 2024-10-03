<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="robots" content="nofollow, noindex">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Include SweetAlert2 and jQuery -->
    <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <!-- Include QRCode.js library -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.qrcode/1.0/jquery.qrcode.min.js"></script>
    <title>UPI Payments</title>
    <style>
        body {
            background: #667eea;
            background: -webkit-linear-gradient(to right, #AFEEF1, #667eea);
            background: linear-gradient(to right, #AFEEF1, #667eea);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
        }
        
        .qr-wrapper {
            padding: 10px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 12px;
        }
        
        .qr-container {
            background: #f2f5fc;
            padding: 0px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 330px;
            border-radius: 8px;
        }
        
        .qr-title {
            background: #343a40;
            color: #fff;
            padding: 10px;
            font-size: 18px;
            border-top-left-radius: 8px;
            border-top-right-radius: 8px;
        }
        
        .qr-code {
            padding: 10px;
            margin: 20px auto;
            display: inline-block;
            border: 4px solid; /* Required for gradient borders */
            border-image-slice: 1;
            border-width: 4px;
            border-image-source: linear-gradient(45deg, #f3ec78, #af4261); /* Gradient border */
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        .amount {
            font-size: 16px;
            margin: 20px 0;
            color: #343a40;
        }
        
        .validity {
            font-size: 12px;
            color: #000000; /* Changing color to black */
        }
        .pay-button, .download-button {
            display: block;
            margin: 20px auto;
            padding: 10px 20px;
            font-size: 16px;
            color: #fff;
            background: #007bff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .pay-button {
            display: none;
        }
        .header {
            background-color: #0A76E9;
            color: white;
            padding: 20px 10px; /* Increase padding: 20px top/bottom, 10px left/right */
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-top-left-radius: 8px; /* Rounded corners on the top left */
            border-top-right-radius: 8px; /* Rounded corners on the top right */
            border-bottom-left-radius: 0; /* No rounded corners on the bottom left */
            border-bottom-right-radius: 0; /* No rounded corners on the bottom right */
        }
        .header img {
            height: 30px; /* Adjust the size of the logo */
            margin-right: 10px;
        }
        .cancel {
            font-size: 24px; /* Size of the cancel symbol */
            cursor: pointer;
        }
                .paytm-button {
            display: block; /* Change from inline-block to block */
            width: 85%; /* Set width to 100% */
            background-color: #E5E5E5 ;
            color: black;
            padding: 10px 20px;
            margin: 10px 0;
            border: 2px solid #1e88e5; /* Dark blue border */
            border-radius: 5px;
            text-decoration: none; /* Remove underline */
            font-size: 16px;
            transition: background-color 0.3s, color 0.3s;
        }

        .paytm-button:hover {
            background-color: #1e88e5; /* Dark blue on hover */
            color: white;
        }

        @media screen and (max-width: 768px) {
            .pay-button {
                display: inline-block;
            }
        }  
       .order-container {
  background-color: darkblue; /* Sets the background color of the container to dark blue */
  color: white;               /* Sets the text color inside the container to white */
  border-radius: 10px;        /* Gives the container rounded corners with a radius of 10px */
  padding: 20px;              /* Adds 20px padding inside the container for spacing */
  width: 86%;                 /* Sets the container's width to 86% of its parent element */
  height: 70px;              /* Sets the container's height to 300 pixels */
 
}

    .order-amount {
      font-size: 20px;
      text-align: left;
      font-weight: bold; /* Making text bold */
    }

    .amount {
  font-size: 30px;
  text-align: center;
  font-weight: bold; /* Making text bold */
  color: white; /* Changing text color to white */
}
/* Hide method-box by default */
.method-box {
    display: none;
}

/* Show method-box on screens smaller than 768px */
@media screen and (max-width: 768px) {
    .method-box {
        display: block;
    }
}


.method-box {
      background-color: white;
      border-radius: 10px;
      padding: 20px;
      margin-top: 20px; /* Add some space between payment and method box */
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Add shadow */
      margin-left: 15px;
      margin-right: 15px;
    }

    .method-header {
      background-color: darkblue;
      color: white;
      padding: 10px 0; /* Adjust padding to make the header full width */
      border-top-left-radius: 10px;
      border-top-right-radius: 10px;
      margin-bottom: 20px; /* Add some space between header and boxes */
    }
    .qr-box {
      background-color: white;
      border-radius: 10px;
      padding: 20px;
      margin-top: 20px; /* Add some space between method box and QR box */
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Add shadow */
      margin-left: 15px;
      margin-right: 15px;
    }

    .qr-header {
      background-color: darkblue;
      color: white;
      padding: 10px 0; /* Adjust padding to make the header full width */
      border-top-left-radius: 10px;
      border-top-right-radius: 10px;
      margin-bottom: 20px; /* Add some space between header and box */
    }

    .qr-image {
      display: block; /* Ensure the image is a block element */
      margin: 0 auto; /* Center the image */
      max-width: 50%; /* Ensure the image does not exceed the container width */
      height: 50%; /* Maintain aspect ratio */
    }
    /* Hide OR text by default */
.or-text {
    display: none;
}

/* Show OR text on screens smaller than 768px */
@media screen and (max-width: 768px) {
    .or-text {
        display: block;
    }
}

    </style>
    </style>
</head>
<?php

header("Content-Security-Policy: 
    default-src 'self'; 
    script-src 'self' https://cdn.jsdelivr.net https://code.jquery.com; 
    style-src 'self' 'unsafe-inline' https://fonts.googleapis.com; 
    img-src 'self' https://api.qrserver.com; 
    font-src 'self' https://fonts.gstatic.com; 
    connect-src 'self'; 
    frame-src 'none'; 
    object-src 'none'; 
    base-uri 'self'; 
    form-action 'self'; 
    upgrade-insecure-requests; 
    block-all-mixed-content;
    frame-ancestors 'none';
");
date_default_timezone_set("Asia/Kolkata");

// Define the base directory constant
define('ROOT_DIR', realpath(dirname(__FILE__)) . '/../');

// Get the protocol (HTTP or HTTPS)
$protocol = (!empty($_SERVER['HTTPS']) && $_SERVER['HTTPS'] !== 'off' || $_SERVER['SERVER_PORT'] == 443) ? "https://" : "http://";

// Get the server name (e.g., www.example.com)
$server_name = $_SERVER['SERVER_NAME'];

// Get the directory path (e.g., /path/to/your/directory)
$directory = dirname($_SERVER['PHP_SELF']);

// Combine to get the base URL
$base_url = $protocol . $server_name . $directory;

// Define the redirect URL using the base URL
$redirect_url = $base_url . '/success.php';

$amount = 399; //Enter Amount 

$upi_id = "webdyno@freecharge"; //Enter UPI ID

$unitId = "Your Name"; //Enter Your Name

$webdynoxnref = "web" . rand(111, 999) . time() . rand(1, 100);
$asdasd23 = time() . rand(11111, 99999);

// Generate Paytm link
$paytm = "paytmmp://cash_wallet?pa=$upi_id&am=$amount&pn=$unitId&tn=$webdynoxnref&tr=$asdasd23&amp;mc=5641&amp;cu=INR&amp;url=&amp;mode=02&amp;purpose=00&amp;orgid=159002&amp;sign=MEUCIHldtBS8sv53BbdI9jtTN4vRokbPT91Fm6wlPQCN/sVkAiEAs4p9TPwTvLvPsceQLjSOBL1lAKhrsHdHMnfiDFyu1Aw=&amp;featuretype=money_transfer";

$orders = "upi://pay?pa=$upi_id&am=$amount&pn=$unitId&tn=$webdynoxnref&tr=$asdasd23";

?>

<body>
    <div class="qr-wrapper">
        <div class="qr-container">
            <div class="header">
                <div style="display: flex; align-items: center;">
                    <img src="/logo.png" alt="Logo"> <!-- Replace 'logo.png' with the path to your logo file -->
                    <span><?php echo $unitId ?></span>
                </div>
                <div class="cancel">&times;</div>
            </div>
            <div class="payment-container">
                    <div class="method-box">
                        <div class="method-header">Method: Direct Pay App</div>
                        <a href="<?php echo $paytm; ?>" class="paytm-button">
                            <img src="https://cashpe.shop/paytm-icon.svg" alt="Paytm Logo" class="paytm-logo" style="width: 20px; height: 15px; margin-right: 10px;">PayTm</a></div><br>
                <div class="or-text">
                    <b>OR</b>
                </div>
                <div class="qr-box">
                    <div class="qr-header">Method: Scan UPI QR</div>
                    <div id="qr-code" class="qr-code"></div>
                    <button id="download-button" class="download-button" onclick="downloadQRCode()">Save QR Code</button>
                <div class="validity">Valid until: <span id="timeout"></div>
 				</div>
 			</div>
 			<div style="padding:10px"></div>
 		</div>
 	</div>  
    <script>
        var paymentProcessed = false;
        var interval;

        // Get server name from PHP
        var serverName = '<?php echo $_SERVER["SERVER_NAME"]; ?>';
        var protocol = '<?php echo $protocol; ?>';

        // Construct the base URL
        var baseUrl = protocol + serverName + '<?php echo $directory; ?>';
        
        var orders = "upi://pay?pa=<?php echo $upi_id; ?>&am=<?php echo $amount; ?>&pn=<?php echo $unitId; ?>&tn=<?php echo $webdynoxnref; ?>&tr=<?php echo $asdasd23; ?>";

        function startTimer(duration, display) {
    var timer = duration, minutes, seconds;
    interval = setInterval(function () {
        minutes = parseInt(timer / 60, 10);
        seconds = parseInt(timer % 60, 10);

        minutes = minutes < 10 ? "0" + minutes : minutes;
        seconds = seconds < 10 ? "0" + seconds : seconds;

        display.textContent = minutes + ":" + seconds;

        if (--timer < 0) {
            clearInterval(interval);
            if (!paymentProcessed) {
                Swal.fire({
                    title: 'Payment Failed',
                    text: 'Time expired. Please try again.',
                    icon: 'error'
                }).then(() => {
                  window.location.href = "/failed.php";

                });
            }
        }
    }, 1000);
}


        function check() {
            if (paymentProcessed || !interval) {
                clearInterval(interval); 
                return;
            }

            $.ajax({
                type: 'POST',
                url: baseUrl + '/status.php',
                data: { 
                    PAYID: '<?php echo $webdynoxnref ?>',
                    amount: '<?php echo $amount; ?>'  // Sending the amount along with the PAYID
                },
                dataType: 'text',
                success: function (data) {
                    if (data === 'success') {
                        paymentProcessed = true;
                        Swal.fire({
                            title: 'Payment Received Successfully ✅',
                            text: 'Please wait...',
                            icon: 'success'
                        }).then(() => {
                            window.location.href = "<?php echo $redirect_url ?>";
                        });
                    } else if (data === 'FAILURE' || data === 'FAILED') {
                        paymentProcessed = true;
                        Swal.fire({
                            title: 'Payment Failed',
                            icon: 'error'
                        }).then(() => {
                            window.location.href = "<?php echo $redirect_url ?>";
                        });
                    }
                },
                error: function (xhr, status, error) {
                    console.log('AJAX Error:', status, error);
                }
            });
        }

        window.onload = function () {
            var fiveMinutes = 60 * 5,
                display = document.querySelector('#timeout');
            startTimer(fiveMinutes, display);
            check();
            interval = setInterval(check, 5000);

            // Generate QR code
            $('#qr-code').qrcode({
                text: orders,
                width: 120,
                height: 120
            });
        };
    </script>
    <script>
     function downloadQRCode() {
    var qrCanvas = document.querySelector('#qr-code canvas');
    if (qrCanvas) {
        // Create a new canvas with extra space for margin
        var canvasWithMargin = document.createElement('canvas');
        var context = canvasWithMargin.getContext('2d');

        // Set new canvas dimensions with added margin
        var margin = 10;
        canvasWithMargin.width = qrCanvas.width + margin * 2;
        canvasWithMargin.height = qrCanvas.height + margin * 2;

        // Fill with white background
        context.fillStyle = '#ffffff';
        context.fillRect(0, 0, canvasWithMargin.width, canvasWithMargin.height);

        // Draw the original QR code onto the new canvas with the margin
        context.drawImage(qrCanvas, margin, margin);

        // Convert the new canvas to an image and download it
        var imgData = canvasWithMargin.toDataURL("image/png");
        var link = document.createElement('a');
        link.href = imgData;
        link.download = 'qr_with_margin.png';
        link.click();
    } else {
        alert('QR Code not yet generated!');
    }
}

    </script>
</body>
</html>
