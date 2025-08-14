## Members

<br>
### Faculty

<table>
  <tbody>
    <tr><th width="80px"> </th><th>Designation</th><th>Name</th></tr>
    {% for faculty in site.faculty %}
    <tr>
      <td><img src="{{ faculty.photo_url }}"></td>
      <td>{{ faculty.designation }}</td>
      <td><a href="{{ faculty.sit_url }}">{{ faculty.name }}</a></td>
    </tr>
    {% endfor %}
  </tbody>
</table>




