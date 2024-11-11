# Max
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative HTML-Only Website with Login</title>
</head>
<body>
    <!-- Header Section -->
    <table width="100%" bgcolor="#333333" cellpadding="20">
        <tr>
            <td align="center">
                <h1 style="color: white;">My Creative HTML-Only Website</h1>
                <p style="color: lightgray;">A project showcasing the power of HTML alone</p>
            </td>
        </tr>
    </table>

    <!-- Navigation Menu -->
    <table width="100%" bgcolor="#555555" cellpadding="10">
        <tr align="center">
            <td><a href="#section1" style="color: white; text-decoration: none;">Home</a></td>
            <td><a href="#section2" style="color: white; text-decoration: none;">About</a></td>
            <td><a href="#section3" style="color: white; text-decoration: none;">Gallery</a></td>
            <td><a href="#section4" style="color: white; text-decoration: none;">Contact</a></td>
            <td><a href="#login" style="color: white; text-decoration: none;">Login</a></td>
        </tr>
    </table>

    <!-- Main Content Section -->
    <table width="100%" cellpadding="20">
        <tr>
            <td align="center">
                <h2 id="section1">Welcome to My Site</h2>
                <p>Explore each section to see how we can achieve different layouts with HTML.</p>
            </td>
        </tr>
    </table>

    <!-- About Section with Columns -->
    <table width="100%" cellpadding="20" bgcolor="#f2f2f2">
        <tr>
            <td colspan="2" align="center">
                <h2 id="section2">About Me</h2>
            </td>
        </tr>
        <tr>
            <td width="50%" align="center">
                <p>I'm a web enthusiast, exploring creative ways to use HTML for building structured layouts.</p>
            </td>
            <td width="50%" align="center">
                <p>HTML alone can do a lot more than expected, especially when used creatively.</p>
            </td>
        </tr>
    </table>

    <!-- Gallery Section -->
    <table width="100%" cellpadding="20">
        <tr>
            <td colspan="3" align="center">
                <h2 id="section3">Gallery</h2>
                <p>Check out these simple placeholder "images" made with HTML tables!</p>
            </td>
        </tr>
        <tr align="center">
            <td width="33%" bgcolor="#d9d9d9">[Image 1]</td>
            <td width="33%" bgcolor="#bfbfbf">[Image 2]</td>
            <td width="33%" bgcolor="#d9d9d9">[Image 3]</td>
        </tr>
        <tr align="center">
            <td width="33%" bgcolor="#bfbfbf">[Image 4]</td>
            <td width="33%" bgcolor="#d9d9d9">[Image 5]</td>
            <td width="33%" bgcolor="#bfbfbf">[Image 6]</td>
        </tr>
    </table>

    <!-- Contact Section -->
    <table width="100%" cellpadding="20" bgcolor="#f2f2f2">
        <tr>
            <td align="center">
                <h2 id="section4">Contact Me</h2>
                <p>Email: <a href="mailto:example@example.com">example@example.com</a></p>
                <p>Phone: 123-456-7890</p>
            </td>
        </tr>
    </table>

    <!-- Login Section -->
    <table width="100%" cellpadding="20" id="login">
        <tr>
            <td align="center">
                <h2>Login</h2>
                <form action="/login" method="POST">
                    <table>
                        <tr>
                            <td><label for="username">Username:</label></td>
                            <td><input type="text" id="username" name="username" required></td>
                        </tr>
                        <tr>
                            <td><label for="password">Password:</label></td>
                            <td><input type="password" id="password" name="password" required></td>
                        </tr>
                        <tr>
                            <td colspan="2" align="center">
                                <input type="submit" value="Login">
                            </td>
                        </tr>
                    </table>
                </form>
                <p style="font-size: small;">Note: This is a static HTML form. A backend is required to handle the login process.</p>
            </td>
        </tr>
    </table>

    <!-- Footer -->
    <table width="100%" bgcolor="#333333" cellpadding="10">
        <tr>
            <td align="center">
                <p style="color: lightgray;">&copy; 2024 My Creative HTML-Only Website</p>
            </td>
        </tr>
    </table>
</body>
</html>
