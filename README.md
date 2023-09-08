<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
</head>
<body class="container bg-warning">
    <h1 class="mt-3 text-center">Support Request Form</h1>
<p class="text-center">Hello, we look forward to resolving your query.</br>
Please fill out the form below and we will get in touch with you as soon as possible.</p>
    <center>

    <form class="form" style="max-width: 500px;">
        <table class="table table-bordered">
            <tr>
                <td><label class="form-label">Full Name</label></td>
                <td><input class="form-control" type="text" /></td>
            </tr>
            <tr>
                <td><label class="form-label">Learner Id</label></td>
                <td><input class="form-control" type="text" /></td>
            </tr>
            <tr>
                <td><label class="form-label">Mobile No.</label></td>
                <td><input class="form-control" type="text" /></td>
            </tr>
            <tr>
                <td><label class="form-label">Email</label></td>
                <td><input class="form-control" type="email" /></td>
                </tr>
                <tr>
                    <td><label class="form-label">Query related to</label></td>
                    <td>
                        <select class="form-select">
                            <option>Option1</option>
                            <option>Option2</option>
                            <option>Option3</option>

                        </select>
                        </td>
                </tr>
                <tr>
                    <td><label class="form-label">Subject</label></td>
                    <td><input class="form-control" type="text" /></td>
                </tr>
                <tr>
                    <td><label class="form-label">Desciption</label></td>
                    <td><textarea class="form-control"></textarea></textarea></td>
                </tr>
                <tr>
                    <td><label class="form-label">Attachment</label></td>
                    <td><input class="form-control" type="file" value="file"/></td>
                </tr>
                <tr>
                    <td colspan="2" class="text-center">
                      <button type="submit" class="btn btn-primary">Sumbit</button>
                      <button type="reset" class="btn btn-outline-primary">
                        Reset
                      </button>
                    </td>
                  </tr>
            
        
        </table>
    </form>
    </center>
</body>
</html>
