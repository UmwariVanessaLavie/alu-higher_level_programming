while count < len(last_list):
                try:
                    new_list.append(last_list[count] + last_list[count + 1])
                    count += 1
                except IndexError:
                    break
