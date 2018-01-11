# Java-Notes

<h3>1.0 Restrict only for letters block numbers and special characters</h3>
```boolean match = usernameField.getText().matches("[a-zA-Z]+");```


<h3>2.0 Get random number between two numbers</h3>
```int randomplayers = min + (int) (Math.random() * max);```

<h3>3.0 Get random element from arraylist</h3>
String alphabet = "BCDFGHJKLMNPQRSTVXZWY";</br>
List<String> values = new ArrayList<>(Arrays.asList(alphabet.split("")));</br>
Collections.shuffle(values);</br>

<h3>4.0 Display message from JOptionPane</h3>
JOptionPane.showConfirmDialog(null, "Total letter count must be 10","", JOptionPane.DEFAULT_OPTION);

<h3>5.0 Append list values to a string </h3>
StringBuilder sb = new StringBuilder();<br>
        for (Character character : letterStack) {<br>
            sb.append(character);<br>
        }<br>

<h3>6.0 Key press event enter key event handle</h3>
if (evt.getKeyCode() == KeyEvent.VK_ENTER) {}






