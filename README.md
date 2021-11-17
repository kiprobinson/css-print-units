# css-print-units
A test for how various browsers handle printing with real-world units like cm

[View test page here](https://tilde.ampersand.space/css-print-units-test/)


<table>
  <tr>
    <th>Browser</th>
    <th>Operating System</th>
    <th>Observations</th>
    <th>Screenshot</th>
    <th>Print to PDF</th>
    <th>Photos of printout with ruler</th>
  </tr>
  <tr>
    <td>Chrome</td>
    <td>Windows</td>
    <td>
      <ul>
        <li>Inline divs print out at correct size.</li>
        <li>On screen, both div and table versions are same size, but when printed the table with 1mm cells is off by about 8 mm after 15 cm.</li>
      </ul>
    </td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/screenshots/Chrome - Windows - Version 96.0.4664.45 (Official Build) (64-bit).png">Chrome - Windows</a></td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/pdfs/Chrome - Windows - Version 96.0.4664.45 (Official Build) (64-bit).pdf">Chrome - Windows</a></td>
    <td>
      <ul>
        <li><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/photos/Chrome - Windows - Version 96.0.4664.45 (Official Build) (64-bit) - 1.jpeg">Chrome - Windows - 1.jpeg</a></li>
        <li><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/photos/Chrome - Windows - Version 96.0.4664.45 (Official Build) (64-bit) - 2.jpeg">Chrome - Windows - 2.jpeg</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Chrome</td>
    <td>Mac</td>
    <td><i>Same as Chrome on Windows</i></td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/screenshots/Chrome - Mac - Version 96.0.4664.45 (Official Build) (x86_64).png">Chrome - Mac</a></td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/pdfs/Chrome - Mac - Version 96.0.4664.45 (Official Build) (x86_64).pdf">Chrome - Mac</a></td>
    <td></td>
  </tr>
  <tr>
    <td>Edge</td>
    <td>Windows</td>
    <td><i>Same as Chrome on Windows</i></td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/screenshots/Edge - Windows - Version 95.0.1020.53 (Official build) (64-bit).png">Edge - Windows</a></td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/pdfs/Edge - Windows - Version 95.0.1020.53 (Official build) (64-bit).pdf">Edge - Windows</a></td>
    <td></td>
  </tr>
  <tr>
    <td>Safari</td>
    <td>Mac</td>
    <td>All versions print out too large - off by about 9.5 mm after 15 cm.</td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/screenshots/Safari - Mac - Version 15.0 (16612.1.29.41.4, 16612).png">Safari - Mac</a></td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/pdfs/Safari - Mac - Version 15.0 (16612.1.29.41.4, 16612).pdf">Safari - Mac</a></td>
    <td>
      <ul>
        <li><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/photos/Safari - Mac - Version 15.0 (16612.1.29.41.4, 16612) - 1.jpeg">Safari - Mac - 1.jpeg</a></li>
        <li><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/photos/Safari - Mac - Version 15.0 (16612.1.29.41.4, 16612) - 2.jpeg">Safari - Mac - 2.jpeg</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Firefox</td>
    <td>Windows</td>
    <td>Pretty much perfect</td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/screenshots/Firefox - Windows - 94.0.1 (64-bit).png">Firefox - Windows</a></td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/pdfs/Firefox - Windows - 94.0.1 (64-bit).pdf">Firefox - Windows</a></td>
    <td>
      <ul>
        <li><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/photos/Firefox - Windows - 94.0.1 (64-bit) - 1.jpeg">Firefox - Windows - 1.jpeg</a></li>
        <li><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/photos/Firefox - Windows - 94.0.1 (64-bit) - 2.jpeg">Firefox - Windows - 2.jpeg</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Firefox</td>
    <td>Mac</td>
    <td><i>Same as Firefox on Windows</i></td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/screenshots/Firefox - Mac - 94.0.1 (64-bit).png">Firefox - Mac</a></td>
    <td><a href="https://raw.githubusercontent.com/kiprobinson/css-print-units/master/pdfs/Firefox - Mac - 94.0.1 (64-bit).pdf">Firefox - Mac</a></td>
    <td></td>
  </tr>
</table>
