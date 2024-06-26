{% from "common/macros.njk" import get_date with context %}

{% set weekly_ip_tasks = {
week2: [
  {id: 'learn_about_the_project'},
  {id: 'set_up_prerequisites'},
  {id: 'set_up_project'},
  {id: 'add_increments', suffix: ' while committing frequently', deadline: get_date(date_w2_start, 4, time=time_lecture_start), increments: [
    {id: 'Level-0', title: 'Rename, Greet, Exit'},
    {id: 'Level-1', title: 'Echo'},
    {id: 'Level-2', title: 'Add, List'},
    {id: 'Level-3', title: 'Mark as Done'},
    {id: 'Level-4', title: 'ToDo, Event, Deadline'},
    {id: 'A-TextUiTesting', title: 'Automated Text UI Testing'},
    {id: 'Level-5', title: 'Handle Errors'},
    {id: 'Level-6', title: 'Delete'},
    {id: 'A-Enums', title: 'Use Enums', tag: 'if-applicable'}
  ]}
],
week3: [
  {id: 'finish_leftover_tasks'},
  {id: 'create_pr_to_upstream'},
  {id: 'add_increments', suffix: ' as branches', increments:  [
    {id: 'Level-7', title: 'Save'},
    {id: 'Level-8', title: 'Dates and Times'}
  ]},
  {id: 'add_increments', suffix: '', increments:  [
    {id: 'A-MoreOOP', title: 'Use More OOP'},
    {id: 'A-Packages', title: 'Organize into Packages'},
    {id: 'A-Gradle', title: 'Use Gradle'},
    {id: 'A-JUnit', title: 'Add JUnit Tests'},
    {id: 'A-Jar', title: 'Create a JAR File'}
  ]},
  {id: 'add_increments', suffix: ' as parallel branches', increments:  [
    {id: 'A-JavaDoc', title: 'JavaDoc'},
    {id: 'A-CodingStandard', title: 'Follow the Coding Standard'},
    {id: 'Level-9', title: 'Find'}
  ]},
  {id: 'start_learning_javafx'}
],
week4: [
  {id: 'use_gfmd_in_pr_description'},
  {id: 'review_two_prs', graded: true, deadline: get_date(date_w4_start, 4, time=time_lecture_start)},
  {id: 'learn_from_others'},
  {id: 'add_increments', suffix: ' as branches', increments:  [
    {id: 'A-CheckStyle', title: 'Use CheckStyle', tag: 'optional'},
    {id: 'Level-10', title: 'GUI'},
    {id: 'A-Varargs', title: 'Use Varargs', tag: 'if-applicable'}
  ]}
],
week5: [
  {id: 'generate_new_jar'},
  {id: 'write_full_commit_messages'},
  {id: 'add_increments', suffix: ' as PRs', increments:  [
    {id: 'A-Assertions', title: 'Use Assertions'},
    {id: 'A-CodeQuality', title: 'Improve Code Quality'},
    {id: 'A-Streams', title: 'Use Streams', tag: 'optional'}
  ]},
  {id: 'add_increments', suffix: '', increments:  [
    {id: 'A-CI', title: 'Set up CI', tag: 'optional'}
  ]},
  {id: 'add_an_extension'}
],
week6: [
  {id: 'add_increments', increments:  [
    {id: 'A-BetterGui', title: 'Better GUI', tag: 'optional'},
    {id: 'A-Personality', title: 'A unique personality', tag: 'optional'},
    {id: 'A-MoreErrorHandling', title: 'More error handling', tag: 'optional'},
    {id: 'A-MoreTesting', title: 'More testing', tag: 'optional'},
    {id: 'A-AiAssisted', title: 'Enhance using AI tools', tag: 'optional'}
  ]},
  {id: 'finalize_features'},
  {id: 'set_up_website'},
  {id: 'submit_the_final_version', deadline: get_date(date_w6_start, 4)}
],
week7: [
  {id: 'get_more_out_of_the_ip'}
],
week8: [
  {id: 'evaluate_peer_ips', deadline: get_date(date_w8_start, 5), graded: true}
]
} %}
